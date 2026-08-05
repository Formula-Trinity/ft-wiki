# Tractive System

### EV4.1 General Requirements

##### EV4.1.1

> The maximum permitted voltage that may occur between any two electrical connections
> is 600VDC and for motor controller/inverters and Accumulator Management System
> (AMS) internal low power control signals 630 VDC.

##### EV4.1.2

> All components in the TS must be rated for the maximum TS voltage.  The TS area of a
> PCB, see EV4.3.6, is considered as one component. Every input connected to the TS must
> be rated to the maximum TS voltage.

##### EV4.1.3

> All components must be rated for the maximum possible temperature that may occur
> during use.

##### EV4.1.4

> Fans with >50W power must not be connected to the TS.

### EV4.2 Tractive System Enclosures

##### EV4.2.1

> Every housing or enclosure containing parts of the TS system, must be labelled with (a)
> reasonably sized sticker(s) according to “ISO 7010-W012” (triangle with black lightning
> bolt on yellow background). The sticker must also contain the text “High Voltage” if the
> voltage is more than 60VDC or 25VAC.

### EV4.3 Separation of Traction System and Grounded Low Voltage System

##### EV4.3.1

> The entire TS and LVS must be galvanically isolated, see EV1.2.1 and IN4.1.1.

##### EV4.3.2

> All connections from a TS component to external devices, such as laptops must include
> galvanic isolation, see EV1.2.1.

##### EV4.3.3

> TS and LVS circuits must be physically segregated such that they are not running through
> the same conduit or connector, except for interlock circuit connections.

##### EV4.3.4

> Where both TS and LVS are present within an TS enclosure, they must be separated by
> barriers made of moisture-resistant insulating materials or maintain 20 mm spacing
> through air, or over a surface.

##### EV4.3.5

> Components and cables capable of movement must be positively restrained to maintain
> spacing.

##### EV4.3.6

> If TS and LVS are on the same PCB, they must be on separate well defined areas of the
> board, meeting the spacing requirements in Table 4, each area clearly marked with “TS”
> or “LV”. The outline of the area required for spacing must be marked.
>
> Grooves and cut-outs must have a minimum width of 1.5 mm to influence the creepage
> path.  “Conformal coating” refers to a coating insulator on a PCB.  Solder resist is not a
> coating.

### Table 4: Spacing required between TS and LV

| Voltage | Clearance Distance | Creepage Distance<br>General | Creepage Distance<br>Conformal Coating |
|---|---:|---:|---:|
| 0VDC to 50VDC | 1.0mm | 4mm | 1.0mm |
| 50VDC to 150VDC | 1.0mm | 5mm | 1.0mm |
| 150VDC to 300VDC | 1.5mm | 10mm | 2.0mm |
| 300VDC to 600VDC | 3.0mm | 20mm | 4.0mm |

<small><em>Spacing required between TS and LV</em></small>

##### EV4.3.7

> Teams must be prepared to demonstrate spacing on team-built equipment. For
> inaccessible circuitry, spare boards must be available.  These do not have to be fully
> assembled.

### EV4.4 Positioning of Tractive System Parts

##### EV4.4.1

> With the exception of what is permitted according to EV4.4.4, all parts belonging to the
> TS including cables and wiring must be located within the rollover protection envelope,
> see T1.1.16. “Part” is the whole device such as the complete HVD.

##### EV4.4.2

> Any part of the TS that is less than 350 mm above the ground, except items permitted by
> EV4.4.3,  must be protected from impacts according to T3.15 and must follow T3.16 when
> having bolted attachments.

##### EV4.4.3

> TS wiring in front of the front roll hoop may alternatively be shielded by the front
> bulkhead support structure according to T3.14.

##### EV4.4.4

> Outboard wheel motors are allowed only if:
> - Interlocks are routed such that the shutdown circuit, see EV6.1, is opened before the
> TS wiring or its connection fails, or in the event of a suspension failure
> - TS wiring is not able to reach the cockpit opening or the driver regardless of where it
> breaks
> - Wiring outside of the rollover protection envelope, see T1.1.16, is minimum length.
> - Wiring outside of an impact structure or front bulkhead support structure, see
> EV4.4.2, is minimum length.
> - Minimum length is the shortest distance plus extra wiring required for suspension /
> steering travel and bend radii.

##### EV4.4.5

> In side or front view any part of the TS must not project below the lower surface of the
> chassis.

##### EV4.4.6

> Additional regulations apply for TS accumulators, see EV5.5.

### EV4.5 Tractive System Insulation, Wiring and Conduit

##### EV4.5.1

> All live parts of the TS must be protected from being touched. This must include team
> members working on or inside the vehicle. This is tested with a 100mm long, 6mm
> diameter insulated test probe when the TS enclosures are in place.

##### EV4.5.2

> Insulation material that is rated for the maximum TS voltage must be used. Using only
> insulating tape or rubber-like paint for insulation is prohibited.

##### EV4.5.3

> The temperature rating for TS wiring, connections and insulation must be appropriate for
> the expected surrounding temperatures but at least 85 °C.

##### EV4.5.4

> TS components and containers must be protected from moisture in the form of rain or
> puddles to a minimum of IPX2, see IN9.

##### EV4.5.5

> It must be possible to clearly assign and prove wire gauge, temperature rating and
> insulation voltage to each used wire.

##### EV4.5.6

> All TS wiring must be completed to professional standards with appropriately sized
> conductors and terminals and with adequate strain relief and protection from loosening
> due to vibration etc.

##### EV4.5.7

> TS wiring must be located out of the way of possible snagging or damage.

##### EV4.5.8

> All TS wiring that runs outside of TS enclosures must
> - Be enclosed in separate orange non-conductive conduit or use an orange shielded
> cable. The conduit must be securely anchored to the vehicle, but not to wire, at least
> at each end,
> - Be securely anchored at least at each end so that it can withstand a force of 200N
> without straining the cable end crimp.
>
> Bodywork is not sufficient to meet this enclosure requirement.

##### EV4.5.9

> Any shielded cable must have the shield grounded.

##### EV4.5.10

> Every TS connector outside of a housing must include a pilot contact/interlock line which
> is part of the shutdown circuit. Housings only used to avoid interlocks are prohibited.

##### EV4.5.11

> All TS connections must be designed so that they use intentional current paths through
> conductors such as copper or aluminium and should not rely on steel bolts to be the
> primary conductor.

##### EV4.5.12

> All TS connections must not include compressible material such as plastic in the stack-up
> or as a fastener. FR-4 is allowed.
>
> NOTE: This rule has been reworked in the Formula Student Germany 2026 Rules, if you
> plan to compete at other events, you must ensure you are compliant with that rule.

##### EV4.5.13

> TS connectors outside of TS enclosures must be designed in a way, that the TS cannot be
> activated, see EV4.11, if connected in any way other than the design intent configuration.

##### EV4.5.14

> All electrical connections, including bolts, nuts and other fasteners, in the high current
> path of the TS must be secured from unintentional loosening by the use of positive
> locking mechanisms that are suitable for high temperatures, see T10.2.
>
> Components, e.g. inverters, certified for automotive use might be allowed without
> positive locking feature, if connections are completed as recommended by the
> manufacturers datasheet and no positive locking is possible.
>
> The team must be able to demonstrate that they have assessed the risk of loosening of
> these connections and describe this and the control methods applied in their ESF.

##### EV4.5.15

> Teams must be prepared to demonstrate positive locking. For inaccessible connections,
> appropriate photographs must be available.

##### EV4.5.16

> Soldered connections in the high current path are only allowed if all of the following are
> true:
> - Connections on PCBs,
> - The connected devices are not cells or wires,
> - The devices are additionally mechanically secured against loosening.

### EV4.6 Energy Meter

##### EV4.6.1

> A calibrated Energy Meter will be provided by the officials and must be inserted during
> competition. The Energy Meter measures TS voltage and TS current.

##### EV4.6.2

> The Datalogger module of the Energy Meter must be in an easily accessible location so
> that it is possible for the officials to check its operation and insert/remove the memory
> stick at any time.

##### EV4.6.3

> The Energy Meter must not be installed within the TSAC.

##### EV4.6.4

> All current supplying the TS must run through the Energy Meter. The Energy Meter must
> be inserted in the negative TS supply between the most negative AIR(s) and the inverters.

##### EV4.6.5

> The TS voltage sense connection of the Energy Meter must be directly connected, see
> T1.3.1, to the most positive AIR(s) on vehicle side.

##### EV4.6.6

> The Energy Meter LV connection must be supplied from the LVMS. The Energy Meter
> requires a stable 12V supply, so regulators or voltage converters are permitted if
> necessary. There should be no switching or relays between the LV source and the Energy
> Meter.

##### EV4.6.7

> The specification of the Energy Meter will be available on the Formula Student website.

### EV4.7 Tractive System Measuring point

##### EV4.7.1

> Two TSMPs must be installed directly next to the master switches, see EV6.2.

##### EV4.7.2

> The TSMPs must be directly connected, see T1.3.1, to the intermediate circuit capacitors
> even if the HVD has been opened or the TS accumulator is disconnected.

##### EV4.7.3

> 4mm shrouded banana jacks of rated for 1000 V CAT III or better must be used.

##### EV4.7.4

> The TSMPs must be marked “TS+” and “TS-” and exclusively mounted on orange back-
> ground.

##### EV4.7.5

> The TSMPs must be protected by a non-conductive housing that can be opened without
> tools.  The cover must always be mechanically linked to the vehicle.

##### EV4.7.6

> Each TSMP must be secured with a current limiting resistor according to Table 5, below.
> Fusing of the TSMPs is prohibited. The resistors power rating must be chosen such that
> they are able to continuously carry the current if both TSMPs are short circuited.

### Table 5: TSMP Resistor requirements

| Maximum TS Voltage | Resistor Value |
|---|---:|
| Umax <200 VDC | 5kΩ |
| 200 VDC <Umax ≤400 VDC | 10kΩ |
| 400 VDC <Umax ≤600 VDC | 15kΩ |

<small><em>TSMP Resistor requirements</em></small>

##### EV4.7.7

> All electrical connections needed for TSMP, including bolts, nuts and other fasteners, must
> be secured from unintentional loosening by the use of positive locking mechanisms.
> Bolted connections must follow T10.2, soldered connections EV4.5.16

##### EV4.7.8

> Next to the TSMPs, a LVS ground measuring point must be installed. A 4mm black
> shrouded banana jack must be connected to LVS ground and must be marked “GND”.

### EV4.8 High Voltage Disconnect

##### EV4.8.1

> It must be possible to disconnect at least one pole of the TS accumulator by quickly
> removing an unobstructed and directly accessible element, fuse or connector. It must be
> possible to disconnect the HVD without removing any bodywork. The HVD must be above
> 350mm from the ground and easily visible when standing behind the vehicle. Remote
> actuation of the HVD through a long handle, rope or wire is not permitted.

##### EV4.8.2

> An untrained person must be able to remove the HVD within 10s when the vehicle is in
> ready-to-race condition.

##### EV4.8.3

> A dummy connector or similar may be required to restore the system’s isolation, see
> EV4.5.  The dummy connector must be green and clearly identifiable to an observer when
> in use.  It must be attached to the push bar, see T1.3.1, if not in use.

##### EV4.8.4

> The HVD must be clearly marked with “HVD”.

##### EV4.8.5

> No tools must be necessary to open the HVD. An interlock is required, see EV4.5.10.

### EV4.9 Discharge Circuit

##### EV4.9.1

> If a discharge circuit is required to meet EV6.1.5, it must be designed to handle the
> maximum TS voltage permanently.
>
> After three subsequent discharges within 15s in total, the discharge time specified in
> EV6.1.5 may be exceeded. Full discharging functionality must be given after a reasonable
> time with a deactivated discharge circuit.

##### EV4.9.2

> The discharge circuit must be wired in a way that it is always active whenever the
> shutdown circuit is open. Furthermore, the discharge circuit must be fail-safe such that it
> still discharges the intermediate circuit capacitors if the HVD has been opened or the TS
> accumulator is disconnected.

##### EV4.9.3

> Fusing of the main current discharge path is prohibited.

### EV4.10 Tractive System Active Light

##### EV4.10.1

> The vehicle must include a single TSAL that must indicate the TS status. The TSAL must not
> perform any other functions. A TSAL with multiple LEDs in one housing is allowed.

##### EV4.10.2

> The TSAL itself must have a red light, flashing continuously with a frequency between 2Hz
> and 5Hz and a duty cycle of 50%, active whenever the LVS is active and for at least 15
> minutes after it is switched off (see Ev4.10.16) and the voltage across any DC-link
> capacitor exceeds the lower of either:
> - 60VDC or 50VACRMS,
> - Half the nominal TS voltage.

##### EV4.10.3

> The TSAL itself must have a green light, continuously on, active whenever the LVS is active
> and for at least 15 minutes after it is switched off (see EV4.10.16) and ALL of the following
> conditions are true:
> - All AIRs are opened.
> - The pre-charge relay, see EV5.7.2, is opened.
> - The voltage at the vehicle side of the AIRs inside the TSAC does not exceed 60VDC or
> 50VACRMS.

##### EV4.10.4

> The voltage detection for the TSAL must be performed inside the respective TS enclosure.

##### EV4.10.5

> The described states of the relays (opened/closed) are the actual mechanical states. The
> mechanical state can differ from the intentional state, i.e. if a relay is stuck. Any circuitry
> detecting the mechanical state must meet EV5.6.2.

##### EV4.10.6

> The voltage detection circuit of the red light and the relay state and voltage detection
> circuit of the green light must be independent. Any plausibility check between both lights
> is not allowed. A TSAL state with both lights simultaneously active might occur and must
> not be prevented.

##### EV4.10.7

> The TSAL must:
> - Be located lower than the highest point of the main hoop and including the mounting
> within the rollover protection envelope, see T1.1.16.
> - Be no lower than 75mm from the highest point of the main hoop.
> - Not be able to contact the driver’s helmet in any circumstances.

##### EV4.10.8

> The entire illuminated surface of the TSAL must be clearly visible:
> - Except for angles less than 10° on each side which are blocked by the main hoop.
> - From a point 1.60m vertically from ground level, within 3m horizontal radius from the
> TSAL.
> - In direct sunlight.

##### EV4.10.9

> The TSAL and all required circuitry must be hard-wired electronics. Software control is
> not permitted.

##### EV4.10.10

> A green indicator light in the cockpit must illuminate if the TSAL green light is on, see
> EV4.10.3. It must be clearly marked “TS off”,  and the light must be easily visible even in
> bright sunlight.

##### EV4.10.11

> Signals influencing the TSAL and the indicator according to EV4.10.10 are SCS, see T11.9.
> The individual safe state of each of the TSAL lights is off. The TSAL has an active indication
> of the absence of failures (continuous green illumination) and thus the red light must not
> be illuminated for a visible check, see T11.9.6.

##### EV4.10.12

> The TSAL’s red light voltage detection circuit, see EV4.10.2, does not need to detect an
> open circuit, as required by T11.9. A plausibility check must not be implemented.

##### EV4.10.13

> Any implausibility in the circuit detecting the AIR and pre-charge relay states (see
> EV4.10.3) must result in the TSAL’s green light being extinguished.  This is exempt from
> the requirement of T11.9.2.

##### EV4.10.14

> Any implausibility between the AIR or pre-charge relay states and the expected voltage
> for these states (see EV4.10.3) must result in the TSAL’s green light being extinguished.
> This is exempt from the requirement of T11.9.2.

##### EV4.10.15

> The latching required by EV4.10.13 and EV4.10.14 must not be triggered during normal
> operation conditions and must only be reset by power cycling the LVS.

##### EV4.10.16

> The TSAL power supply must:
> - Comply with T11.7 and be capable of powering the TSAL for at least 15 minutes after
> the LVS has been switched off.  It is permissible for the TSAL to be powered by the LVS
> whenever this is switched on.
> - Not be used to power any other systems,
> - Comply with all requirements of T11.1 but must not be de-activated by opening the
> LVMS (see T11.3).

##### EV4.10.17

> It is permissible for the ESO to deactivate the TSAL when the LVS is switched off and if the
> TS is confirmed to be deactivated.
> - It must not be possible to activate the TS if the TSAL is in a deactivated state,
> - The driver must not be able to deactivate the TSAL.

### EV4.11 Activating the Tractive System

##### EV4.11.1

> The TS is active if any of the AIRs or the pre-charge relay are closed.

##### EV4.11.2

> The driver must be able to activate and deactivate the TS from within the cockpit without
> the assistance of any other person.

##### EV4.11.3

> [DV ONLY] The ASR must be able to activate the TS from outside the vehicle with an
> external TS activation button in proximity to the TSMS if and only if the ASMS is in “On”
> position.

##### EV4.11.4

> Closing the shutdown circuit by any part defined in EV6.1.2 must not (re-)activate the TS.
> Additional action must be required.

##### EV4.11.5

> [DV ONLY] The AS must not be able to (re-)activate the TS.

##### EV4.11.6

> The vehicle is ready-to-drive as soon as the motor(s) will respond to the input of the
> APPS.

##### EV4.11.7

> After the TS has been activated, additional actions must be required by the driver to set
> the vehicle to ready-to-drive mode (e.g. pressing a dedicated start button). The transition
> to ready-to-drive mode must only be possible during the actuation of the mechanical
> brakes and a simultaneous dedicated additional action.

##### EV4.11.8

> The ready-to-drive mode must be left immediately when the shutdown circuit is
> opened.

### EV4.12 Ready-To-Drive Sound

##### EV4.12.1

> The vehicle must make a characteristic sound, continuously for at least one second and a
> maximum of three seconds while entering ready-to-drive mode.

##### EV4.12.2

> The sound level must be a minimum of 90dB(A), fast weighting. The sound level will be
> measured with a free-field microphone placed free from obstructions in a radius of 2m
> around the vehicle.

##### EV4.12.3

> The sound must be easily recognisable. No animal voices, parts of songs or sounds that
> could be interpreted as offensive are permissible.

##### EV4.12.4

> The vehicle must not make any other sounds similar to the ready-to-drive sound.
