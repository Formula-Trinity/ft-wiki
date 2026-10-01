# Safety Circuit Monitor (SCM)

## Why do we need it?

The shutdown circuit is a chain of safety devices wired one after another (in series), including the BSPD, inertia switch, BOTS and the three shutdown buttons. If any one of them opens, the engine stops. The Safety Circuit Monitor is a circuit board that watches this chain and lights a dashboard LED to show which device has opened it.

## FTX7

On FTX6, the shutdown circuit was shown to the driver as a series of LEDs, each corresponding to a different stage. If a device was triggered, all the LEDs after it would also turn off, which made the display hard to read for anyone who didn't know how it was wired. For FTX7 the SCM was designed to work out which device was triggered and light only that device's LED.

The SCM has six channels, one each for the BSPD, inertia switch, BOTS, cockpit, left and right shutdown buttons. Each channel looks at the shutdown circuit just before and just after its device. If the point before is live but the point after is not, that device must be the one that has opened, so its LED turns on.

The design report notes that the only limitation of this approach is that it shows the most upstream failure, because the shutdown switches are single pole. If two devices are open at the same time, only the first one in the chain is shown.

The SCM schematic shows two 7-way terminal blocks. One takes the inputs from the shutdown circuit and the other provides the six LED outputs and a ground.

The [Electronics Overview](../../index.md) notes a safety concern with the connection point on the PCB. The wires are very close together, so a short could potentially bypass part of the shutdown circuit. It suggests moving the power supply on the PCB further away from the monitoring points, or using a proper PCB connector such as a Molex instead of a screw terminal.
