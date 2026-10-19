# MegaSquirt 3 (MS3)

**Status:** Draft  
**System:** Engine Management  
**Vehicle:** Bruce  

## Da Blurb

The MegaSquirt 3 (MS3) is the main engine-management controller used on Bruce.

It processes information from engine sensors and uses this information, together with the stored engine calibration, to determine how the engine should be controlled.

Its main responsibilities include controlling fuel injection and ignition timing.

## System Role

The ECU sits between the engine sensors and engine actuators.

A simplified representation is:

Sensors → MS3 ECU → Engine Control Outputs

Typical sensor information used by the ECU includes:

- crankshaft position;
- camshaft position, where applicable;
- throttle position (TPS);
- manifold absolute pressure (MAP);
- manifold / intake air temperature (MAT);
- coolant temperature (CLT);
- lambda / air-fuel information.

The ECU uses these measurements to determine the current operating state of the engine.

It then controls outputs including:

- fuel injectors;
- ignition system;
- rev-limiter behaviour;
- other configurable engine-management outputs.

## ECU Hardware

The current Bruce ECU arrangement uses MegaSquirt 3 hardware together with an MS3X expansion board.

Current team notes describe the ECU as containing three PCBs:

1. the main MegaSquirt board;
2. the MS3 processor board;
3. an additional expansion / connectivity board.

The exact identity and purpose of each PCB should be confirmed from the physical ECU and team schematics.

### MS3X

The MS3X expansion board increases the number of inputs and outputs available to the MS3 system.

This allows the ECU to interface with additional engine sensors and actuators without requiring all functions to be handled by the original mainboard.

The exact MS3X inputs and outputs currently used by Bruce should be documented from the wiring loom and ECU configuration.

## Engine Position

One of the ECU's most important inputs is the crankshaft position signal.

A sensor observes a toothed wheel associated with the crankshaft. As the wheel rotates, the sensor produces an electrical signal corresponding to the passing teeth.

The ECU uses the timing between these signals to determine engine speed.

For example:

Number of teeth detected per second  
→ number of crankshaft revolutions per second  
→ engine RPM

A known reference point in the trigger pattern also allows the ECU to determine crankshaft position.

If a camshaft position sensor is used, this provides additional information allowing the ECU to determine the phase of the four-stroke engine cycle.

This timing information is required so that fuel injection and ignition occur at the correct point in the engine cycle.

## Calibration

The MS3 behaviour is determined partly by its calibration.

Important parameters include:

- ignition timing;
- ignition dwell;
- fuel tables;
- injector configuration;
- crank / cam trigger configuration;
- rev limiter;
- fuel cut;
- spark cut;
- sensor calibrations;
- temperature corrections.

The current vehicle calibration should be treated as controlled configuration and changes should be documented.

## Communications

The ECU can provide engine information to other vehicle systems.

This allows information such as engine speed, temperatures and other telemetry to be made available to the dashboard or data-logging systems without requiring each system to have its own duplicate engine sensors.

The exact communication arrangement used on Bruce should be documented separately.

