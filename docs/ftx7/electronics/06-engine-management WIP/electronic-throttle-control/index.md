# Electronic Throttle Control (Optional)

**Owner:**  
**Status:**  
**ECU / controller:**  

> Delete this folder when the car uses a mechanical throttle.

## Sensors and actuator

| Item | Quantity | Range | Supply | ECU channel | Safety-critical? |
|---|---:|---|---|---|---|
| APPS |  |  |  |  |  |
| TPS | 2 minimum |  |  |  |  |
| Throttle motor | 1 |  |  |  |  |

## Plausibility and fault detection

Document APPS plausibility, TPS-to-TPS plausibility, target-vs-actual monitoring, time limits, sensor open/short detection and the reaction to each fault.

## Return-to-idle design

- Mechanical return springs:
- Actuator power-off behaviour:
- Time to idle:
- Verification evidence:
- Failure response if idle is not reached:

## Power-stage shutdown

Show how throttle actuator power is removed and how ignition, injection and fuel-pump power is disabled when required.

## Calibration

- APPS endpoints:
- TPS endpoints:
- Pedal-to-throttle map:
- Limp / shutdown strategy:
- Calibration access control:

## Inspection tests

Provide reproducible steps for every safety feature and error-detection demonstration.

## Open issues

- [ ]
