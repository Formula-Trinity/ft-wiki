# Safety Circuit Monitor (SCM)

**Owner:**  
**Status:**  
**Hardware revision:**  
**Firmware revision:**  

## Purpose

Define what the SCM monitors, logs or indicates. State clearly whether it is observation-only or whether it can open the SDC.

## Safety boundary

- Required safety function implemented by SCM:
- Functions explicitly not implemented by SCM:
- Programmable elements:
- Non-programmable output stage, if it opens the SDC:
- Behaviour with SCM unplugged:
- Behaviour with SCM unpowered:
- Behaviour after watchdog reset:
- Can any SCM fault keep the SDC closed when it should be open?

## Monitored nodes

| Node | Meaning | Normal voltage / state | Fault interpretation | Logged channel |
|---|---|---|---|---|
|  |  |  |  |  |

## Interfaces

| Interface | Direction | Isolation / protection | Connector / pin | Notes |
|---|---|---|---|---|
| SDC sense | Input |  |  |  |
| SDC open command, if present | Output |  |  |  |
| CAN | I/O |  |  |  |
| Indicator outputs | Output |  |  |  |

## State machine and indications

Document power-up, healthy, warning, shutdown, latched fault and reset states. Add a state diagram.

## Diagnostics

- Fault codes:
- LED meanings:
- CAN messages:
- Event log format:
- Timestamp source:
- Data retention:
- Service tool:

## Fault injection and independence tests

Prove that shorts, opens, loss of ground, MCU lockup, corrupted firmware and CAN faults cannot bypass the mandatory SDC devices.

## Open issues

- [ ]
