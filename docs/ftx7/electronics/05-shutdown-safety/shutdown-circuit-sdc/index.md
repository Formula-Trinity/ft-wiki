# Shutdown Circuit (SDC)

**Owner:**  
**Status:**  
**Last reviewed:**  
**Applicable ruleset and version:**  

## Purpose and safe state

Define exactly what the SDC removes power from. For an IC car, document how it directly controls the electrical power to the fuel pump, ignition and injection through the required relay arrangement.

## Complete SDC chain

Record the physical series order and wire identifiers.

| Order | Element | Normal state | Trigger | Reset method | Connector / wire |
|---:|---|---|---|---|---|
| 1 | LVMS |  |  |  |  |
| 2 | BSPD |  |  |  |  |
| 3 | Cockpit shutdown button |  |  |  |  |
| 4 | Left shutdown button |  |  |  |  |
| 5 | Right shutdown button |  |  |  |  |
| 6 | BOTS |  |  |  |  |
| 7 | Inertia switch |  |  |  |  |

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
