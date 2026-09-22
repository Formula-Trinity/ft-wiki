# Shutdown Circuit (SDC)

**Owner:**  
**Status:**  
**Last reviewed:**  
**Applicable ruleset and version:**  

## Purpose and safe state

The Shutdown Circuit (SDC) is a series circuit in charge of shutting the engine down when triggered. It is composed of six components as described in Rule [CV4.1](../../../rules/section-cv/4-shutdown-system.md/#cv41-shutdown-circuit), the SDC is powered directly by the LVMS.

## Complete SDC chain

| Order | Element | Normal state | Trigger | Reset method |
|---:|---|---|---|---|
| 1 | [BSPD](../../01-components/safety/BSPD.md) | Open | Safe Condition | 10s Self Reset |  
| 2 | [Inertia](../../01-components/safety/inertia.md) | Closed | Exceed G limit | Push Reset |  
| 3 | [BOTS](../../05-shutdown-safety/brake-over-travel-switch-bots/index.md) | Closed | Loss of Brake Pressure | Pull Reset |  
| 4 | [Cockpit shutdown button](../../01-components/safety/emergency-switch.md) | Closed | Manual | Pull Reset | 
| 5 | [Left shutdown button](../../01-components/safety/emergency-switch.md) | Closed | Manual | Pull Reset | 
| 6 | [Right shutdown button](../../01-components/safety/emergency-switch.md) | Closed | Manual | Pull Reset | 

## Schematics

- Full current-path schematic
- Relay-coil schematic
- Fuel-pump relay path
- Ignition/injection relay path
- Fuse and overcurrent protection
- Test points and service disconnects

## Operating states

| State | SDC continuity | Fuel pump | Ignition / injection | SCM indication |
|---|---|---|---|---|
| LVMS off |  |  |  |  |
| Ready |  |  |  |  |
| Any shutdown element open |  |  |  |  |
| Reset attempt |  |  |  |  |

## De-energized behaviour

Explain why every required element opens the SDC when de-energized or disconnected. Identify any semiconductor or programmable element and prove that it cannot defeat the required safety function.

## Relay selection and calculations

- Coil voltage and current:
- Contact rating and inrush:
- Flyback suppression:
- Minimum wire size:
- Voltage-drop budget:
- Failure mode of suppression components:

## Verification and fault injection

| Test | Method | Expected result | Evidence |
|---|---|---|---|
| Open each SDC element individually |  | Engine stops / cannot start |  |
| Disconnect each SDC device |  | SDC opens |  |
| Welded-contact analysis |  | Required independent shutdown remains |  |
| Low-voltage test |  | Safe response |  |
| Harness short/open tests |  | Safe response |  |

## Scrutineering demonstration

Write a step-by-step demonstration that a new team member can perform without design knowledge.

## Open issues

- [ ]
