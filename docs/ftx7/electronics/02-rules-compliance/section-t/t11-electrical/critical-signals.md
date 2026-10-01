# T11.9 — System Critical Signals

[Rules and Compliance](../../index.md) / [Section index](index.md)

Record the FTX7 critical-signal inventory against the linked rules. The overview identifies an SCM connection-area short that could bypass shutdown elements; this remains an open design concern.

**Owner:** Electronics; shared interfaces require the relevant subsystem owner.<br>
**Ruleset:** Formula Student 2026 V1 — repository copy.<br>
**Review:** Entries remain open until the specified evidence is recorded. See the register status definitions.

## Design and evidence locations

- [Electronics Overview](../../../index.md)
- [SCM](../../../01-components/safety/SCM.md)
- [MS3](../../../01-components/engine/MS3.md)
- [Pinouts](../../../08-wiring-harness/pinouts/index.md)
- [Bench Tests](../../../10-testing-validation/bench-tests/index.md)

## Rules on this page

| Rule | Topic | Status |
|---|---|---|
| [T11.9.1](#t1191) | Identify every critical signal | Open |
| [T11.9.2](#t1192) | Detect signal failures | Open |
| [T11.9.3](#t1193) | Failure after a corrected fault | Open |
| [T11.9.4](#t1194) | Digital message timeout | Conditional |
| [T11.9.5](#t1195) | Safe and error states | Open |
| [T11.9.6](#t1196) | Indicator lamp check | Conditional |
| [T11.9.7](#t1197) | Failure-mode documentation | Open |

## T11.9.1 — Identify every critical signal {#t1191}

**Rule:** [T11.9.1](../../../../rules/section-t/11-electrical-components.md#t1191)<br>
**Status:** Open

**FTX7 compliance approach:** Build a register covering BSPD inputs, shutdown interfaces and ECU torque-related sensors/commands. Classify SCM taps by their possible influence on the SDC.

**Verification needed:** Attach a signal-by-signal inventory with source, destination, pins and classification.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## T11.9.2 — Detect signal failures {#t1192}

**Rule:** [T11.9.2](../../../../rules/section-t/11-electrical-components.md#t1192)<br>
**Status:** Open

**FTX7 compliance approach:** The overview describes BSPD out-of-range detection but gives no complete fault results. Include the documented SCM bypass concern and all relevant ECU signals in the review.

**Verification needed:** Attach fault-injection results for every applicable fault class and the resulting connected-system state.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## T11.9.3 — Failure after a corrected fault {#t1193}

**Rule:** [T11.9.3](../../../../rules/section-t/11-electrical-components.md#t1193)<br>
**Status:** Open

**FTX7 compliance approach:** Document any ECU fallback or redundant safety path and show when continued operation ends.

**Verification needed:** Test the applicable combinations of initial corrected and subsequent uncorrectable faults.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## T11.9.4 — Digital message timeout {#t1194}

**Rule:** [T11.9.4](../../../../rules/section-t/11-electrical-components.md#t1194)<br>
**Status:** Conditional

**FTX7 compliance approach:** The overview says there is no CAN bus and describes a USB dashboard link. Determine whether any digital connection influences SCS functions before marking this conditional clause not applicable.

**Verification needed:** Attach the interface classification and, where applicable, timeout settings and tests.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## T11.9.5 — Safe and error states {#t1195}

**Rule:** [T11.9.5](../../../../rules/section-t/11-electrical-components.md#t1195)<br>
**Status:** Open

**FTX7 compliance approach:** The documented shutdown outcome removes fuel-pump, ignition and injector power. Assign the required state per signal; merely stopping an ECU output may not establish the required open SDC.

**Verification needed:** Attach a signal/state table and measured fault responses.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## T11.9.6 — Indicator lamp check {#t1196}

**Rule:** [T11.9.6](../../../../rules/section-t/11-electrical-components.md#t1196)<br>
**Status:** Conditional

**FTX7 compliance approach:** Classify the SCM/dashboard indicators against T11.9.1 before applying this requirement. No lamp-check implementation is documented.

**Verification needed:** Record applicability and, where required, a timed startup demonstration.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## T11.9.7 — Failure-mode documentation {#t1197}

**Rule:** [T11.9.7](../../../../rules/section-t/11-electrical-components.md#t1197)<br>
**Status:** Open

**FTX7 compliance approach:** Prepare the FTX7 SCS failure analysis and results. Record the event-specific CV submission route with references to the linked rule, [EV9](../../../../rules/section-ev/9-electrical-system-form.md) and any event clarification.

**Verification needed:** Attach the SCS analysis and any applicable current-season submission guidance or clarification.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

[Back to section index](index.md) · [Back to Rules and Compliance](../../index.md)
