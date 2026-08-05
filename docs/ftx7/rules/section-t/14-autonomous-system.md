# [DV Only] Autonomous System

### T14.1 Definitions

##### T14.1.1

> Each vehicle must implement a full AS according to T14, to run in autonomous mode.

##### T14.1.2

> [CV ONLY] The following definitions apply to maintain the same wording as for Electric
> Vehicles:
> - Ready-to-drive (R2D) – Engine is running, and a gear is engaged,
> - TS active – Engine is running but gearbox is in neutral (also assumed for TS not active),
> - TS activation button – The engine start button is the equivalent,
> - Accumulator Isolation Relay (AIR) - The fuel pump relay (see Figure 21) is the equivalent.

### T14.2 Teleoperated driving

##### T14.2.1

> Teleoperated driving is not allowed.

### T14.3 Data logger

##### T14.3.1

> The officials may provide a standardised data logger that must be installed during the
> competition. Further specifications for the data logger and required hardware and software
> interfaces can be found on the Formula Student Website.

##### T14.3.2

> The intent of the data logger is to understand and reproduce the system state in case of
> failure. This includes a basic set of signals defined on the Formula Student Website and the
> set of vehicle-individual signals that have to be monitored by the Autonomous System
> Brake (ASB) to ensure redundancy and fault detection.

### T14.4 Remote Emergency System

##### T14.4.1

> Every vehicle must be equipped with a standard RES specified on the Formula Student
> Website. The system consists of two parts, the remote control and the vehicle module.

##### T14.4.2

> The RES must be purchased by the team.

##### T14.4.3

> The RES has two functions:
> - When the remote emergency stop button is pressed, it must open the DV Shutdown
> Circuit (SDC) defined in T14.5,
> - When the “Go” button is pressed, the preselected autonomous mission is started.

##### T14.4.4

> The RES vehicle module must be directly integrated in the vehicle’s SDC with one of its
> relays hard-wired in series to the shutdown buttons.

##### T14.4.5

> The RES relay, which is integrated into the SDC, must be bypassed by a normally closed
> relay, when driving manually. The relay must be directly supplied by the ASMS, see T14.6,
> and must have either a forcibly guided or a mirrored normally open contact which is
> directly connected in series to the ASMS.

##### T14.4.6

> The antenna of the RES must be mounted unobstructed and without interfering parts in
> proximity (other antennas, etc.).

### T14.5 Shutdown Circuit

##### T14.5.1

> If the SDC is opened by the AS or the RES, it has to be latched open by a non-programmable
> logic that can only be reset manually (either via a button outside of the vehicle, in proximity
> to the ASMS, or via LVMS power cycle).

##### T14.5.2

> The SDC may only be closed by the AS, if the following conditions are fulfilled:
> - Manual Driving: Manual Mission is selected, the AS has checked that ASB is deactivated
> (No autonomous brake actuation possible),
> - Autonomous Driving: Autonomous Mission is selected, ASMS is switched on and
> sufficient brake pressure is built up (brakes are closed).

### T14.6 Autonomous System Master Switch

##### T14.6.1

> Each vehicle must be equipped with an ASMS, according to T11.2.

##### T14.6.2

> The ASMS must be mounted in the middle of a completely blue circular area of ≥50 mm
> diameter placed on a high contrast background.

##### T14.6.3

> The ASMS must be marked with “AS”.

##### T14.6.4

> The power supply of the steering and braking actuators must be switched by
> - LVMS,
> - ASMS,
> - The normally-open contact of the RES bypass relay.
>
> Other than stated in T11.2.1, non-programmable logic may be used as part of the ASMS.

##### T14.6.5

> When the ASMS is in “Off” position, the following must be fulfilled:
> - No steering, braking and propulsion actuation can be performed by request of the
> autonomous system,
> - The sensors and the processing units can stay operational,
> - The vehicle must be able to be pushed as specified in A6.7,
> - It must be possible to operate the vehicle manually as a normal CV or EV.

##### T14.6.6

> It is strictly forbidden to switch the ASMS to the “On” position if a person is inside the
> vehicle.

##### T14.6.7

> After switching the ASMS to the “On” position, the vehicle may not start moving, until the
> “AS driving” state is entered (Figure 17).

##### T14.6.8

> The ASMS must be fitted with a “lockout/tagout” capability to prevent accidental activation
> of the AS. The ASR must ensure that the ASMS is locked in the off position whenever the
> vehicle is outside the dynamic area or driven in manual mode.

### T14.7 Steering Actuation

##### T14.7.1

> Steering system actuation (movement) must only happen if the vehicle is R2D.

##### T14.7.2

> The steering system may remain active during an emergency brake manoeuvre while the
> vehicle is in movement.

##### T14.7.3

> Manual steering must be possible without manual release steps (e.g. operating manual
> valves / (dis-) connecting mechanical elements) while the ASMS is switched “Off”.

### T14.8 Actuator Decoupling

##### T14.8.1

> It is not allowed to remove any parts of the autonomous system for dynamic events.

##### T14.8.2

> The actuators may be disconnected for manual driving if:
> - No parts are removed for disconnection,
> - The disconnection mechanism cannot block manual operation in any position,
> - The disconnection mechanism is securely locked in both positions.

### T14.9 Autonomous System Status Definitions

##### T14.9.1

> The Emergency Brake System (EBS) is considered to be “activated”, if its power supply is cut
> after passing the initial check-up sequence (T15.3.1). Brakes may only be released by
> operating the deactivation points defined in T15.1.7. .

##### T14.9.2

> The EBS is no longer considered to be activated if all brakes have been released using the
> deactivation points defined in [T15.1.7]

##### T14.9.3

> The status of the AS must be determined according to the flowchart in Figure 22.

<div style="height: 248px;" aria-hidden="true"></div>

<small><em>Figure 22: AS Status Flowchart</em></small>

##### T14.9.4

> R2D may only be activated by the “Go” signal from the RES, after the system has remained
> in “AS Ready” for at least 5s.

##### T14.9.5

> Performing manual steps, other than activating the TS, at the car while the ASMS is
> switched “On” is prohibited.

### T14.10 Autonomous System Status Indicators

##### T14.10.1

> The vehicle must include three ASSIs that must indicate the status of the AS (as defined in
> T14.10) correlating to illumination as shown:
>
> AS Off AS Ready AS Driving AS Emergency AS Finished
> off yellow yellow flashing blue flashing blue continuous
> continuous
>
> The ASSIs may not perform any other functions.

##### T14.10.2

> One ASSI must be located on each side of the vehicle behind the driver’s compartment, in a
> region 160mm below the top of the main hoop and 600mm above the ground. The third
> ASSI must be located at the rear of the vehicle, on the vehicle centreline, near vertical,
> 160mm below the top of the main hoop and more than 100mm above the brake light.

##### T14.10.3

> At least one ASSI must be visible from any angle of the vehicle from a point 1.6m vertically
> from ground level, within a 3m horizontal radius from the top of the main hoop.

##### T14.10.4

> Each ASSI must meet the requirements of a System Status Light, according to T11.10.

##### T14.10.5

> The status “AS Emergency” has to be indicated by an intermittent sound with the following
> parameters:
> - On-/off-frequency: 1Hz to 5Hz,
> - Duty cycle 50%,
> - Sound level greater than 80dBA, fast weighting in a radius of 2m around the vehicle,
> - Duration between 8s and 10s after entering “AS Emergency”.

### T14.11 Autonomous Missions

##### T14.11.1

> The AS must at least implement the following missions:
> - Acceleration,
> - Skidpad,
> - [DC ONLY] Autocross,
> - [DC ONLY] Trackdrive,
> - EBS test,
> - Inspection,
> - Manual driving.

##### T14.11.2

> The inspection mission will be used during technical inspection while the vehicle is jacked
> up and all wheels are removed.

##### T14.11.3

> The inspection mission is defined by slowly spinning the drivetrain and actuating the
> steering system with a sine wave. After 25s to 30s the mission is finished and the transition
> to “AS Finish” must be initialized.

##### T14.11.4

> It must be possible to select any mission without the use of an external device.

##### T14.11.5

> The selected mission must be indicated by the Autonomous Mission Indicator (AMI).

##### T14.11.6

> The AMI must be easily readable and can either be part of the dashboard or located next to
> the ASMS. If an e-ink display is used, it must be visible that the shown mission is up to date.
> The AMI is considered SCS.

### T14.12 Autonomous System Form

##### T14.13

> Prior to the competition, all teams must submit a clearly structured documentation of their
> entire AS (including ASB) called ASF.
