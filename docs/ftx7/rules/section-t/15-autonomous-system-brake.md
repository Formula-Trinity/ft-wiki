# [DV Only] Autonomous System Brake

### T15.1 Technical Requirements

##### T15.1.1

> To run in autonomous mode, the vehicle must be equipped with an ASB that features an
> EBS as part of it (see T15.2).

##### T15.1.2

> All parts of the ASB and their mountings must be located within the rollover protection
> envelope, see T1.1.16. With the following exceptions:
> - brake system according to T6,
> - deactivation points according to T15.1.7.

##### T15.1.3

> The TS is not considered to be a brake system.

##### T15.1.4

> Manual braking must always be possible.

##### T15.1.5

> Brake master cylinders must not be connected in series.

##### T15.1.6

> The ASB may be part of the hydraulic brake system. For all components of pneumatic and
> hydraulic brake actuation not covered by T6, T9 is applied.

##### T15.1.7

> The ASB must be designed so that it can be easily deactivated by a maximum of two
> deactivation points.

##### T15.1.8

> All deactivation points of the ASB must:
> - Work without the aid of electrical power,
> - Be in proximity to each other,
> - Be mounted in the surface envelope,
> - Either be mounted in proximity to the ASMS or on the top side of the vehicle between
> front bulkhead and front hoop close to the vehicles centre line,
> - Be protected against unintended actuation, e.g. by hitting a cone while driving,
> - Be operable by maximum two simple push/pull and/or turning actions, the order and
> direction of these actions must be shown next to the deactivation points,
> - Be marked with “Brake release”,
> - Have a red handle.

##### T15.1.9

> The use of push-in fittings is prohibited in function critical pneumatic circuits of the ASB
> and any other system which uses the same energy storage without proper decoupling.

### T15.2 Emergency Brake System

##### T15.2.1

> The EBS must only use passive systems with mechanical energy storage. Electrical power
> -loss at EBS must lead to a direct emergency brake manoeuvre with the performance
> specified in T15.4.

##### T15.2.2

> The EBS must be directly supplied by LVMS, ASMS, RES and a relay which is supplied by the
> SDC (parallel to the AIRs but must not be delayed).

### T15.3 Functional Safety

##### T15.3.1

> An initial check has to be performed to ensure the ASB is able to build up brake pressure as
> expected, before AS transitions to “AS Ready”.

##### T15.3.2

> After the initial check the ASB and its SCS must be continuously monitored for failures.

##### T15.3.3

> A red indicator light in the cockpit that is easily visible from inside and outside the cockpit
> even in bright sunlight and clearly marked with the lettering “ASB” must light up if the SDC
> is opened due to an ASB failure.

##### T15.3.4

> The vehicle must automatically transition to the safe state, if:
> - The functionality according to T15.2.1 cannot be ensured,
> - An (additional) single point of failure would lead to total loss of brake capability.

##### T15.3.5

> The safe state is the vehicle at a standstill, brakes engaged to prevent the vehicle from
> rolling, and an open SDC.

##### T15.3.6

> To get to the safe state, the vehicle must perform an autonomous brake manoeuvre
> described in section T15.4 and IN6.2.

### T15.4 Emergency Brake System Performance

##### T15.4.1

> The system reaction time (the time between opening of the SDC and the start of the
> deceleration) must not exceed 200ms.

##### T15.4.2

> The average deceleration must be greater than 10m/s2 under dry track conditions.

##### T15.4.3

> In case of a single failure the ASB should be designed to achieve at least half of the
> performance specified in T15.4.2.

##### T15.4.4

> Whilst decelerating, the vehicle must remain in a stable driving condition.

##### T15.4.5

> The performance of the system will be tested at technical inspection, see IN6.2.
