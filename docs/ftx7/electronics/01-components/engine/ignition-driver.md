

The ignition driver provides the electrical interface between the MegaSquirt ECU and the ignition coils.

The ECU produces a low-power ignition control signal, but the primary winding of an ignition coil requires a much larger current. The ignition driver allows the ECU to control this current without the high ignition-coil current passing directly through the ECU output.

Bruce uses external ignition drivers because the ignition coils are "dumb" coils and do not contain their own high-current switching electronics.

![Quadspark with Harness](../images/quadspark_with_harness.jpg#right)

## Connection

A simplified ignition connection is:

ECU → Ignition Driver → Ignition Coil → Spark Plug

The ignition driver contains a high-current semiconductor switching device, such as an IGBT or MOSFET depending on the design. In this case a MOSFET is used.

When commanded by the ECU, the driver switches on and allows current to flow through the primary winding of the ignition coil.

The current remains on for a period known as the **dwell time**. During this period, energy is stored in the magnetic field of the ignition coil.

When the ECU commands the ignition driver to switch off, the primary current is interrupted rapidly. The magnetic field in the ignition coil collapses and a high voltage is generated in the secondary winding, producing the voltage required for the spark plug.

## Protection

Ignition coils are highly inductive loads. Interrupting the primary current can produce large voltage transients.

The ignition driver must therefore be designed to tolerate and control these transients using suitable voltage-clamping and protection circuitry.

