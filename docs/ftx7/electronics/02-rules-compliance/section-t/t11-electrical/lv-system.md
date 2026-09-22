# T11.1 — Low Voltage System

[Rules and Compliance](../../index.md) / [Section index](index.md)

The electronics overview describes a 12 V system. Nominal battery voltage alone does not establish the maximum voltage anywhere in the installation.

**Owner:** Electronics; shared interfaces require the relevant subsystem owner.<br>
**Ruleset:** Formula Student 2026 V1 — repository copy.<br>
**Review:** Entries remain open until the specified evidence is recorded. See the register status definitions.

## Design and evidence locations

- [Electronics Overview](../../../index.md)
- [Electrical Architecture](../../../03-electrical-architecture/index.md)
- [Charging System](../../../03-electrical-architecture/charging-system/index.md)

## Rules on this page

| Rule | Topic | Status |
|---|---|---|
| [T11.1.1](#t1111) | LVS boundary | Open |
| [T11.1.2](#t1112) | Voltage limits | Open |
| [T11.1.3](#t1113) | Insulation | Open |
| [T11.1.4](#t1114) | CV voltage exceptions | Open |
| [T11.1.5](#t1115) | Motor control signals | Conditional |
| [T11.1.6](#t1116) | EV wiring colour | Not applicable |
| [T11.1.7](#t1117) | EV chassis grounding | Not applicable |

## T11.1.1 — LVS boundary {#t1111}

**Rule:** [T11.1.1](../../../../rules/section-t/11-electrical-components.md#t1111)<br>
**Status:** Open

**FTX7 compliance approach:** Include the ECU, ignition, injection, charging, dashboard, safety devices and auxiliaries in the electrical-system drawing.

**Verification needed:** Review the complete power and signal schematic against the component register.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## T11.1.2 — Voltage limits {#t1112}

**Rule:** [T11.1.2](../../../../rules/section-t/11-electrical-components.md#t1112)<br>
**Status:** Open

**FTX7 compliance approach:** FTX7 is documented as nominally 12 V. Record maximum operating voltages, including charging and converters, for every circuit outside the permitted exceptions.

**Verification needed:** Attach voltage ratings and measured worst-case values.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## T11.1.3 — Insulation {#t1113}

**Rule:** [T11.1.3](../../../../rules/section-t/11-electrical-components.md#t1113)<br>
**Status:** Open

**FTX7 compliance approach:** Document insulation of wires, terminals, busbars, PCBs and connectors; the present architecture pages do not establish this.

**Verification needed:** Inspect the installed harness and covers; attach photographs and insulation specifications.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## T11.1.4 — CV voltage exceptions {#t1114}

**Rule:** [T11.1.4](../../../../rules/section-t/11-electrical-components.md#t1114)<br>
**Status:** Open

**FTX7 compliance approach:** Identify the ignition and injector drive circuits and establish whether the charging system qualifies as OEM equipment. An exception to voltage limits does not waive insulation.

**Verification needed:** Attach circuit boundaries and relevant component datasheets.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## T11.1.5 — Motor control signals {#t1115}

**Rule:** [T11.1.5](../../../../rules/section-t/11-electrical-components.md#t1115)<br>
**Status:** Conditional

**FTX7 compliance approach:** No propulsion motor controller is described. Confirm the fitted equipment before recording this clause as not applicable.

**Verification needed:** Check the final component register for any motor controller or inverter.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## T11.1.6 — EV wiring colour {#t1116}

**Rule:** [T11.1.6](../../../../rules/section-t/11-electrical-components.md#t1116)<br>
**Status:** Not applicable

**FTX7 compliance approach:** The documented combustion configuration is outside this clause.

**Verification needed:** Reassess if the vehicle class changes.

**Evidence / result:** Documented configuration basis; final fitment confirmation pending.

## T11.1.7 — EV chassis grounding {#t1117}

**Rule:** [T11.1.7](../../../../rules/section-t/11-electrical-components.md#t1117)<br>
**Status:** Not applicable

**FTX7 compliance approach:** The documented combustion configuration is outside this clause. Record FTX7 grounding design in the electrical architecture.

**Verification needed:** Reassess if the vehicle class changes.

**Evidence / result:** Documented configuration basis; final fitment confirmation pending.

[Back to section index](index.md) · [Back to Rules and Compliance](../../index.md)
