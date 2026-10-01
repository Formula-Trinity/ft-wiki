# CV4 — Shutdown System

[Rules and Compliance](../index.md) / [Section index](index.md)

The overview describes independent fuel-pump and ignition/injection relays. The detailed relay page is unfilled, and the SCM short-circuit concern needs a documented resolution.

**Owner:** Electronics; shared interfaces require the relevant subsystem owner.<br>
**Ruleset:** Formula Student 2026 V1 — repository copy.<br>
**Review:** Entries remain open until the specified evidence is recorded. See the register status definitions.

## Design and evidence locations

- [Electronics Overview](../../index.md)
- [Shutdown Circuit (SDC)](../../04-shutdown-safety/shutdown-circuit-sdc/index.md)
- [Ignition, Injection and Fuel-Pump Shutdown Relays](../../04-shutdown-safety/shutdown-relays/index.md)
- [SCM](../../01-components/safety/SCM.md)

## Rules on this page

| Rule | Topic | Status |
|---|---|---|
| [CV4.1.1](#cv411) | Remove power from all engine loads | Open |
| [CV4.1.2](#cv412) | Required series devices | Open |
| [CV4.1.3](#cv413) | De-energized and disconnected behaviour | Open |

## CV4.1.1 — Remove power from all engine loads {#cv411}

**Rule:** [CV4.1.1](../../../rules/section-cv/4-shutdown-system.md#cv411)<br>
**Status:** Open

**FTX7 compliance approach:** The documented architecture uses a fuel-pump relay and a separate ignition/injection relay. Prove the final load wiring removes power independently of ECU commands.

**Verification needed:** Attach load-path schematics, relay specifications and shutdown measurements at every controlled load.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## CV4.1.2 — Required series devices {#cv412}

**Rule:** [CV4.1.2](../../../rules/section-cv/4-shutdown-system.md#cv412)<br>
**Status:** Open

**FTX7 compliance approach:** These devices appear in the overview chain. Trace the complete installed circuit, including the LVMS and all SCM monitoring branches.

**Verification needed:** Attach the series-circuit drawing and individual-device opening tests.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

## CV4.1.3 — De-energized and disconnected behaviour {#cv413}

**Rule:** [CV4.1.3](../../../rules/section-cv/4-shutdown-system.md#cv413)<br>
**Status:** Open

**FTX7 compliance approach:** Document normally-open relay operation and device failure responses. Resolve the overview's possible SCM short that could bypass safety elements; a proposed connector change is not evidence of resolution.

**Verification needed:** Attach disconnect and loss-of-power results, plus an analysis and verification of the SCM connection design.

**Evidence / result:** Pending — add the evidence link, result, configuration/revision, reviewer and date.

[Back to section index](index.md) · [Back to Rules and Compliance](../index.md)
