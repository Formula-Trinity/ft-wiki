# Brake System Plausibility Device (BSPD)

## Why do we need it?

The BSPD is a small standalone safety circuit that monitors how hard the driver is braking (using the brake pressure sensor) and how far the throttle is open (using the throttle position sensor). If the driver is braking hard while the throttle is also open, something is wrong, for example a stuck throttle. If this lasts for too long, the BSPD opens the shutdown circuit and the engine stops.

"Plausibility" refers to checking that the two signals make sense together e.g. hard braking with an open throttle is not a plausible combination.

The rules require every car to have a BSPD, and it must be a standalone, non-programmable circuit. This means it cannot use a microcontroller or any software.

## FTX7

For FTX6 the BSPD design was taken from another team. For FTX7 the BSPD was designed from scratch so that the team is not reliant on others' designs and can change the design in the future if the rules change.

The rules allow the BSPD to reset either by power cycling the LVMS or by resetting itself once the fault has been gone for more than 10 s. The design report states that the 10 s self-resetting option was chosen because it removes the need for external human input.

The [Electronics Overview](../../index.md) lists the BSPD trip thresholds as 25% throttle and hard braking with no locked wheels at under 30 bar, with a trip delay of 500 ms and a reset 10 s after the condition is removed.

### How the circuit works

The BSPD schematic shows the main parts of the circuit:

- The board takes 12 V from the car through a 150 mA fuse and a transient voltage suppression diode (SMF18A), which protects against voltage spikes. A regulator (TPS7B6950) then provides 5 V for the logic.
- LM339 comparators compare the throttle and brake pressure signals against thresholds set by two adjustable trimmers. A logic gate then detects when both thresholds are exceeded at the same time.
- Other comparators check that each sensor signal is between 0.45 V and 2.27 V. A signal outside this range, such as from a broken or shorted wire, is also treated as a fault.
- An RC timer and an LM311 comparator make sure the fault has to last for a set time before the BSPD trips.
- A 555 timer provides the timed self-reset.
- A transistor drives an Omron G5Q-1A relay, and the shutdown circuit passes through this relay's contacts. The G5Q-1A has a normally open contact, so if the BSPD loses power the relay opens and so does the shutdown circuit.

The board also has LEDs showing power, throttle fault, brake pressure fault, sensor fault and the output state.

The BSPD connects to the car through a single 6-way terminal block with the following pins:

1. brake pressure sensor input
2. throttle position sensor input
3. 12 V supply
4. ground
5. shutdown circuit output
6. shutdown circuit input
