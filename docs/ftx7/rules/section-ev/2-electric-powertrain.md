# Electric Powertrain

### EV2.1 Motors

##### EV2.1.1

> Only electric motors are allowed.

##### EV2.1.2

> Motor attachments must follow T10.

##### EV2.1.3

> Motor casings must follow T7.3.

##### EV2.1.4

> The motor(s) must be connected to the accumulator through a motor controller.

### EV2.2 Power Limitation

##### EV2.2.1

> The TS power, measured by the Energy Meter, must not exceed +80kW or 500A,
> whichever is lower.

##### EV2.2.2

> Negative TS power (regenerating energy), measured by the Energy Meter, is permissible
> and unrestricted for power, but the 500A current limit applies.

##### EV2.2.3

> Supplying power to the motor(s) such that the car is driven in reverse is prohibited.

### EV2.3 APPS / Brake Pedal Plausibility Check

##### EV2.3.1

> The commanded motor torque must be 0 Nm, if the mechanical brakes are actuated and
> the APPS, see T11.8, signals pedal travel equivalent to >25% desired motor torque or
> >5kW, whichever is lower, at the same time, for longer than 500ms.

##### EV2.3.2

> The commanded motor torque must remain at 0Nm until the APPS signals less than 5%
> pedal travel and 0Nm desired motor torque, regardless of whether the brakes are still
> actuated or not.
