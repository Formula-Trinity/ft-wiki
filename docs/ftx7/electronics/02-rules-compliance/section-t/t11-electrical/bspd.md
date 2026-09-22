# T11.6 — Brake System Plausibility Device

[Rules and Compliance](../../index.md) / [Section index](index.md)

The overview describes a custom non-programmable BSPD using throttle position and brake pressure. Its stated thresholds and timing are design intentions; measured trip and reset results are not attached.

**Owner:** Electronics; shared interfaces require the relevant subsystem owner.<br>
**Ruleset:** Formula Student 2026 V1 — repository copy.<br>
**Review:** Entries remain open until the specified evidence is recorded. See the register status definitions.

## Design and evidence locations

- [Electronics Overview](../../../index.md)
- [BSPD](../../../01-components/safety/BSPD.md)
- [TPS](../../../01-components/sensors/TPS.md)
- [BPS](../../../01-components/sensors/BPS.md)
- [Bench Tests](../../../10-testing-validation/bench-tests/index.md)

## Rules on this page

| Rule | Topic | Status |
|---|---|---|
| [T11.6.1](#t1161) | Independent brake/throttle shutdown | Open |
| [T11.6.2](#t1162) | Implausibility persistence | Open |
| [T11.6.3](#t1163) | Direct LVMS supply | Open |
| [T11.6.4](#t1164) | Standalone boards and interfaces | Open |
| [T11.6.5](#t1165) | Hard-braking threshold | Open |
| [T11.6.6](#t1166) | EV current measurement | Not applicable |
| [T11.6.7](#t1167) | Sensor disconnection access | Open |
| [T11.6.8](#t1168) | Critical signals | Open |
| [T11.6.9](#t1169) | EV power simulation test | Not applicable |
| [T11.6.10](#t11610) | EV accumulator location | Not applicable |

## T11.6.1 — Independent brake/throttle shutdown {#t1161}

**Rule:** [T11.6.1](../../../../rules/section-t/11-electrical-components.md#t1161)<br>
**Status:** Open

**FTX7 compliance approach:** The overview describes this circuit and a 10 s self-reset. Compare the measured calibration and reset behaviour, including tolerances, with the linked rule.

**Verification needed:** Attach the schematic, threshold calculation, latch/reset traces and engine shutdown demonstration.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## T11.6.2 — Implausibility persistence {#t1162}

**Rule:** [T11.6.2](../../../../rules/section-t/11-electrical-components.md#t1162)<br>
**Status:** Open

**FTX7 compliance approach:** The overview states a 500 ms trip delay with an asterisk. Record actual circuit timing and component tolerances.

**Verification needed:** Capture input conditions and SDC output around the 500 ms boundary.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## T11.6.3 — Direct LVMS supply {#t1163}

**Rule:** [T11.6.3](../../../../rules/section-t/11-electrical-components.md#t1163)<br>
**Status:** Open

**FTX7 compliance approach:** The overview shows the LVMS upstream. Trace the actual BSPD supply against the linked rule and [T1.3.1](../../../../rules/section-t/1-definitions.md#t131).

**Verification needed:** Attach a highlighted supply schematic and wire/pin references.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## T11.6.4 — Standalone boards and interfaces {#t1164}

**Rule:** [T11.6.4](../../../../rules/section-t/11-electrical-components.md#t1164)<br>
**Status:** Open

**FTX7 compliance approach:** The BSPD and SCM are described as separate custom units. Document their board functions, monitoring connections and ECU interfaces against the linked rule.

**Verification needed:** Review PCB layouts, connector pinouts and the complete sensor/supply routing.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## T11.6.5 — Hard-braking threshold {#t1165}

**Rule:** [T11.6.5](../../../../rules/section-t/11-electrical-components.md#t1165)<br>
**Status:** Open

**FTX7 compliance approach:** The overview states a threshold below 30 bar with no locked wheels. The actual pressure calibration and vehicle correlation are missing.

**Verification needed:** Attach pressure calibration and a vehicle result demonstrating threshold actuation without wheel lock.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## T11.6.6 — EV current measurement {#t1166}

**Rule:** [T11.6.6](../../../../rules/section-t/11-electrical-components.md#t1166)<br>
**Status:** Not applicable

**FTX7 compliance approach:** FTX7 uses the CV throttle-position criterion.

**Verification needed:** Reassess if the powertrain class changes.

**Evidence / result:** Documented configuration basis; final fitment confirmation pending.

## T11.6.7 — Sensor disconnection access {#t1167}

**Rule:** [T11.6.7](../../../../rules/section-t/11-electrical-components.md#t1167)<br>
**Status:** Open

**FTX7 compliance approach:** Provide individual disconnect points for the brake-pressure and throttle-position signals.

**Verification needed:** Record connector/pin locations and demonstrate each disconnection.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## T11.6.8 — Critical signals {#t1168}

**Rule:** [T11.6.8](../../../../rules/section-t/11-electrical-components.md#t1168)<br>
**Status:** Open

**FTX7 compliance approach:** Include supply, required sensors and shutdown interfaces in the critical-signal review. Out-of-range behaviour is described but not tested in the wiki.

**Verification needed:** Attach the signal fault matrix and results linked to each signal.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## T11.6.9 — EV power simulation test {#t1169}

**Rule:** [T11.6.9](../../../../rules/section-t/11-electrical-components.md#t1169)<br>
**Status:** Not applicable

**FTX7 compliance approach:** Use the CV brake/throttle demonstration for FTX7; this EV-specific test is outside the documented configuration.

**Verification needed:** Reassess if the powertrain class changes.

**Evidence / result:** Documented configuration basis; final fitment confirmation pending.

## T11.6.10 — EV accumulator location {#t11610}

**Rule:** [T11.6.10](../../../../rules/section-t/11-electrical-components.md#t11610)<br>
**Status:** Not applicable

**FTX7 compliance approach:** No tractive-system accumulator is described for this combustion car.

**Verification needed:** Reassess if the powertrain class changes.

**Evidence / result:** Documented configuration basis; final fitment confirmation pending.

[Back to section index](index.md) · [Back to Rules and Compliance](../../index.md)
