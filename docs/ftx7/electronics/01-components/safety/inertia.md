# Inertia Switch

## Why do we need it?

An inertia switch is a mechanical switch that opens automatically if the car experiences a large, sudden deceleration such as in a crash. Once triggered it stays open until someone resets it by hand.

After a crash, the driver may be injured or unable to switch the car off. Because the inertia switch is part of the shutdown circuit, an impact will automatically cut power to the fuel pump, injectors and ignition, stopping the engine and the flow of fuel.

The rules require an inertia switch in the shutdown circuit. It must latch until it is manually reset and must not contain any semiconductor components.

## FTX7

For FTX7, the inertia switch is wired in series in the shutdown circuit after the [BSPD](./BSPD.md) and before the BOTS. The [Safety Circuit Monitor](./SCM.md) has an LED that lights when the inertia switch has opened the shutdown circuit.

The [Electronics Overview](../../index.md) lists the device as a Sensata Crash Sensor, which is the sensor the rules name as one that should meet the requirements. 
