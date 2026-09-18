# Rules and Compliance

This section records the Formula Student rules applicable to the FTX7 electrical system and the evidence used to demonstrate compliance.

**Owner:** Electronics \
**Status:** Released \
**Last reviewed:** 30/07/2026 \
**Applicable ruleset:** Formula Student 2026 V1

## Scope

This section covers electrical and electronic requirements applicable to FTX7, including safety-critical systems, shutdown behaviour, electrical protection, required indicators, system interfaces and supporting compliance evidence.

It provides traceability between:

`Rule → Requirement → Implementation → Test → Evidence`

Detailed subsystem design is documented within the relevant technical sections of the wiki.

## Pages

* [Rules Register](./rules-register/index.md) — applicable rules, interpretations and compliance status
* [Safety-Critical Signals](./safety-critical-signals/index.md) — signals whose state or failure can affect vehicle safety
* [Requirements Traceability](./requirements-traceability/index.md) — links requirements to implementation, verification and evidence

## Compliance Summary

The FTX7 electrical system was reviewed against the applicable Formula Student ruleset during design, build and validation.

For each applicable requirement, the documentation should identify:

* the originating rule;
* the resulting engineering requirement;
* the subsystem or component responsible for compliance;
* the verification method;
* the associated test or inspection evidence.

Where a rule is not applicable to FTX7, the reason should be recorded in the [Rules Register](./rules-register/index.md).

## Safety-Critical Requirements

Safety-related requirements should document the expected system behaviour under both normal and fault conditions.

Where applicable, verification should include:

* loss of power;
* open circuits;
* short circuits;
* loss of communication;
* invalid sensor states;
* component or controller failure;
* activation of shutdown devices.

The required safe state and measurable acceptance criteria should be defined before the associated evidence is considered complete.

## Compliance Evidence

Evidence supporting electrical compliance is stored alongside the relevant requirement or test record.

Typical evidence includes:

* schematics and electrical drawings;
* connector and pin definitions;
* calculations;
* inspection records;
* test procedures and results;
* measurements and data logs;
* photographs;
* firmware and calibration versions;
* scrutineering documentation.

See [Scrutineering and Evidence](../13-scrutineering-evidence/index.md) for the final inspection and competition evidence set.

## Final Compliance State

The released documentation in this section represents the final FTX7 electrical configuration.

Any deviations from the documented configuration, unresolved requirements or rule interpretations should be explicitly recorded in the relevant page rather than assumed compliant.
