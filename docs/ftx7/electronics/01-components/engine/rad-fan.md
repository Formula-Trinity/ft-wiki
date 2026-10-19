# Radiator Fan

**Status:** Draft  
**System:** Engine Cooling / Auxiliary Electrical  
**Vehicle:** Bruce  

## Da Blurb

The radiator fan provides forced airflow through the radiator when natural airflow through the vehicle is insufficient.

The radiator transfers heat from the engine coolant to the surrounding air. At low vehicle speed or while stationary, there may not be enough airflow through the radiator to adequately cool the engine.

The radiator fan increases this airflow and therefore assists in controlling engine coolant temperature.

## Operation

During vehicle motion, air naturally passes through the radiator.

At low speed or while stationary, the radiator fan can be switched on to provide additional airflow.

A simplified cooling path is:

Engine → Hot Coolant → Radiator → Airflow → Heat Removed

With fan assistance:

Electrical Supply → Fan Motor → Increased Radiator Airflow

The coolant temperature sensor (CLT) allows the engine-management system to monitor engine temperature.

Depending on Bruce's current wiring and calibration, the radiator fan may be switched automatically when coolant temperature passes a configured threshold.

The exact switching strategy should be verified against the ECU configuration and wiring diagram.

## Electrical Control

A radiator fan motor can draw substantially more current than an ECU output or low-current switch is designed to provide directly.

The fan is therefore normally controlled using a relay or suitable power-switching device.

A typical arrangement is:

ECU / Control Signal → Relay → Radiator Fan

The control side requires relatively little current.

The relay then switches the larger current required by the fan motor.

The exact Bruce fan-control circuit should be confirmed from the electrical schematic.

## Control Strategy

Possible fan-control parameters include:

- fan-on coolant temperature;
- fan-off coolant temperature;
- hysteresis between the on and off temperatures;
- manual override, if fitted;
- fan operation during engine shutdown, if implemented.

The actual values used on Bruce should be copied from the current ECU configuration rather than assumed.

Using different fan-on and fan-off temperatures prevents the fan rapidly switching on and off when coolant temperature sits directly around one threshold.

For example:

Fan switches on at upper threshold  
→ coolant temperature falls  
→ fan remains on  
→ fan switches off at lower threshold


## Inspection / Testing

Useful checks include:

- inspect fan blades for damage;
- ensure the fan rotates freely;
- inspect the mounting points;
- inspect wiring and connectors;
- verify the fuse and relay;
- command the fan on and confirm operation;
- confirm correct direction of airflow;
- confirm the configured fan-on and fan-off temperatures;
- monitor coolant temperature during testing.

