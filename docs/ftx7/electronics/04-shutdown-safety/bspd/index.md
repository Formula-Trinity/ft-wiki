# Brake System Plausibility Device (BSPD)

**Owner:**  
**Status:**  
**PCB revision:**  
**Applicable ruleset and version:**  

## Safety function

Describe the standalone, non-programmable path that opens the SDC when hard braking and excessive throttle occur together for longer than the permitted persistence time.

## Inputs and thresholds

| Input | Sensor | Electrical range | Threshold | Tolerance | Disconnectable for inspection? |
|---|---|---|---|---|---|
| Brake pressure |  |  |  |  | Yes / No |
| Throttle position |  |  |  |  | Yes / No |
| LVMS-direct supply |  |  |  |  |  |

## Timing and reset behaviour

- Implausibility persistence delay:
- Latch/reset strategy:
- Automatic reset delay, if used:
- Power-cycle behaviour:
- Startup behaviour:
- Brownout behaviour:

## Independence

Document:
- Why the circuit is non-programmable
- Why required signals do not pass through another device first
- How parallel sensor users are prevented from interfering
- How loss of supply, ground or sensor wiring produces a safe result
- Which PCB features are BSPD-only

## Circuit design

Add:
- Comparator calculations
- Hysteresis
- Timing calculations and worst-case tolerances
- Output stage and SDC current capability
- Input protection
- Reverse-polarity and transient protection
- Test points

## Failure analysis

| Fault | Detection / effect | SDC response | Test |
|---|---|---|---|
| Brake sensor open |  |  |  |
| Brake sensor short to ground / supply |  |  |  |
| TPS open |  |  |  |
| TPS short to ground / supply |  |  |  |
| BSPD supply lost |  |  |  |
| Comparator stuck |  |  |  |
| Timing component tolerance extreme |  |  |  |
| Output device failed |  |  |  |

## Verification

Include threshold sweeps, timing captures, temperature corners, supply-voltage corners, sensor-disconnect tests and SDC load tests.

## Inspection procedure

Give exact connector pins, test equipment, stimulus values and expected LEDs/relay states.

## Open issues

- [ ]
