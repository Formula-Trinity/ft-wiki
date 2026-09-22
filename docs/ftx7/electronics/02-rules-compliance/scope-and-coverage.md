# Scope and Rules-Folder Coverage

[Rules and Compliance](index.md)

Every Markdown chapter under `docs/ftx7/rules` was read for this register, including A, T, CV, EV, AFV, IN, S and D. The table records the electronics relevance of each chapter. A listed chapter is not necessarily applicable in full: individual clauses are selected for the documented combustion configuration and shared interfaces.

The working entry is a running, manually driven CV in FS Class. Confirm the entry class, final equipment and event rules revision. Requirements owned by chassis, brakes, powertrain or the competition-document teams remain applicable to the vehicle and are not waived by being outside this electronics register.

[Applicability assumptions and conditional systems](conditional-systems.md)

[Complete source rules register](../../rules/index.md) · [Rule abbreviations](../../rules/abbreviations.md)

## A

| Source chapter | Review outcome | Compliance entries |
|---|---|---|
| [Competition Overview](../../rules/section-a/1-competition-overview.md) | T and CV define the documented vehicle scope; the remaining competition format is team-wide. | [A1 / A3 — Ruleset and Clarifications](section-a/ruleset.md) |
| [Vehicle Eligibility](../../rules/section-a/2-vehicle-eligibility.md) | Student design, eligibility and chassis-year requirements remain team-wide; no separate electronics hardware clause. | Shared/team-owned; see review outcome. |
| [Rules of Conduct](../../rules/section-a/3-rules-of-conduct.md) | Rule authority and clarification control are included; conduct, protests and advertising remain team-wide. | [A1 / A3 — Ruleset and Clarifications](section-a/ruleset.md) |
| [General Requirements for Teams & Participants](../../rules/section-a/4-general-req.md) | Registration, insurance and team eligibility are team-wide. ESO/ESA are EV-only and ASR is DV-only; see conditional systems. | [Applicability review](conditional-systems.md) |
| [Documentation & Deadlines](../../rules/section-a/5-docs-deadlines.md) | Electronics document contributions are included; the team submission owners retain the complete A5 requirements. | [A5 — Electronics Documentation and Submissions](section-a/submissions.md) |
| [General Rules](../../rules/section-a/6-general-rules.md) | CV testing, engine running, radios and telemetry are included. Other site conduct is team-wide; EV/DV procedures are conditional. | [A6 — Testing, Engine Running and Work Safety](section-a/operations.md)<br>[A6.13 — Team Radios and Telemetry](section-a/radios-telemetry.md) |

---

## T

| Source chapter | Review outcome | Compliance entries |
|---|---|---|
| [Definitions](../../rules/section-t/1-definitions.md) | Electrical connection, material and installation-envelope definitions are included. | [T1 — Definitions Used by Electronics](section-t/t1-definitions.md) |
| [General Design Requirements](../../rules/section-t/2-general-design-requirements.md) | Electronic installation interfaces are included; overall vehicle geometry, tyres and suspension are owned by the relevant teams. | [T2 — General Design and Electrical Installation](section-t/t2-general-design.md) |
| [General Chassis Design](../../rules/section-t/3-general-chassis-design.md) | Mounting holes, inspection access and front-sensor impact interfaces are included. Chassis retains material, structure and SES proof, including T3.2/T3.15/T3.16 where invoked by an installation. | [T3 — Chassis Interfaces and Front Sensors](section-t/t3-chassis.md) |
| [Cockpit](../../rules/section-t/4-cockpit.md) | Cockpit access, driver controls, heat protection and firewall interfaces are included. T4.3 supplies the full master-switch height template. | [T4 — Cockpit, Firewall and Driver Access](section-t/t4-cockpit.md) |
| [Driver Restraint System](../../rules/section-t/5-driver-restraint-system.md) | Electrical sharp-edge and inspection-cover interfaces are included; restraints and structural driver protection remain chassis-owned. | [T5 — Driver Protection Interfaces](section-t/t5-driver-protection.md) |
| [Brake System](../../rules/section-t/6-brake-system.md) | BOTS and brake light are included in full, plus shared hydraulic interfaces. Hydraulic design and pedal strength remain brakes-owned. | [T6.2 — Brake Over-Travel Switch](section-t/t6-brakes/bots.md)<br>[T6.3 — Brake Light](section-t/t6-brakes/brake-light.md)<br>[T6.1 — Brake System Interfaces](section-t/t6-brakes/general.md) |
| [Powertrain](../../rules/section-t/7-powertrain.md) | Power-off movement, temperature-rated sensor interfaces and stationary rotating-part guards are included. Other drivetrain/cooling design remains powertrain-owned. | [T7 — Powertrain Electrical Interfaces](section-t/t7-powertrain.md) |
| [Aerodynamic Devices](../../rules/section-t/8-aerodynamic-devices.md) | Powered airflow prohibition and conditional aero-actuator envelope are included. Aero owns the full device strength, stability and edge requirements. | [T8 — Powered Aerodynamics Interfaces](section-t/t8-aerodynamics.md) |
| [Critical Components](../../rules/section-t/9-critical-fasteners.md) | Conditional for hybrid storage, pneumatic actuation, high-pressure hydraulics or gaseous fuel; no such installation is established in the overview. | [Applicability review](conditional-systems.md) |
| [Fasteners](../../rules/section-t/10-fasteners.md) | Applicable critical-fastener interfaces are included. OEM retaining rings, steering bearings and tie rods remain with their subsystem owners. | [T10 — Critical Fasteners at Electrical Interfaces](section-t/t10-fasteners.md) |
| [Electrical Components](../../rules/section-t/11-electrical-components.md) | All subsections are addressed: T11.1–T11.7 and T11.9–T11.11 have individual entries; T11.8 is explicitly conditional on EV/ETC. EV-only subclauses are labelled. | [T11.1 — Low Voltage System](section-t/t11-electrical/lv-system.md)<br>[T11.2 — Master Switches](section-t/t11-electrical/master-switches.md)<br>[T11.3 — Low Voltage Master Switch](section-t/t11-electrical/lvms.md)<br>[T11.4 — Shutdown Buttons](section-t/t11-electrical/shutdown-buttons.md)<br>[T11.5 — Inertia Switch](section-t/t11-electrical/inertia-switch.md)<br>[T11.6 — Brake System Plausibility Device](section-t/t11-electrical/bspd.md)<br>[T11.7 — Low Voltage Batteries](section-t/t11-electrical/lv-battery.md)<br>[T11.9 — System Critical Signals](section-t/t11-electrical/critical-signals.md)<br>[T11.10 — System Status Light](section-t/t11-electrical/status-light.md)<br>[T11.11 — Sensors and Electrical Components Mounting](section-t/t11-electrical/mounting.md) |
| [Vehicle Identification](../../rules/section-t/12-vehicle-identification.md) | Timing equipment is included; vehicle graphics are team-wide. Hybrid/EV/AFV identification changes are conditional. | [T12.3 — Timing Equipment](section-t/t12-timing.md) |
| [Vehicle and Driver Equipment](../../rules/section-t/13-vehicle-and-driver-equipment.md) | Camera requirements are included; driver equipment, supports and extinguishers are shared prerequisites referenced by operating/inspection rules. | [T13.5 — Cameras and Recording Equipment](section-t/t13-cameras.md) |
| [[DV Only] Autonomous System](../../rules/section-t/14-autonomous-system.md) | DV-only; conditional on adding autonomous operation. | [Applicability review](conditional-systems.md) |
| [[DV Only] Autonomous System Brake](../../rules/section-t/15-autonomous-system-brake.md) | DV-only; conditional on adding autonomous operation. | [Applicability review](conditional-systems.md) |

---

## CV

| Source chapter | Review outcome | Compliance entries |
|---|---|---|
| [Internal Combustion Engine Powertrains](../../rules/section-cv/1-internal-combustion-engine-powertrains.md) | Starter and throttle/TPS interfaces are included. ETC and DV starting are conditional; engine, intake and mechanical return-system design remain powertrain-owned. | [CV1 — Starter and Throttle Interfaces](section-cv/cv1-starter-throttle.md) |
| [Fuel and Fuel System](../../rules/section-cv/2-fuel-and-fuel-system.md) | Fuel selection, pump/injector/sensor placement, pressure classification and ignition spill protection are included; powertrain owns the full fluid-system requirements. | [CV2 — Fuel and Injection Interfaces](section-cv/cv2-fuel-injection.md) |
| [Exhaust System and Noise Control](../../rules/section-cv/3-exhaust-system-and-noise-control.md) | Exhaust geometry and shielding remain powertrain-owned. Electronics supports noise validation under IN10 and nearby-component thermal checks. | Shared/team-owned; see review outcome. |
| [Shutdown System](../../rules/section-cv/4-shutdown-system.md) | All three shutdown clauses have individual compliance entries. | [CV4 — Shutdown System](section-cv/cv4-shutdown.md) |
| [LV Hybrid System](../../rules/section-cv/5-lv-hybrid-system.md) | Conditional LV hybrid system; no propulsion motor or hybrid store is documented. | [Applicability review](conditional-systems.md) |

---

## EV

| Source chapter | Review outcome | Compliance entries |
|---|---|---|
| [Definitions](../../rules/section-ev/1-definitions.md) | EV chapter reviewed; outside the documented CV configuration unless an applicable T, CV5 or AFV rule explicitly imports a provision. See conditional systems. | [Applicability review](conditional-systems.md) |
| [Electric Powertrain](../../rules/section-ev/2-electric-powertrain.md) | EV chapter reviewed; outside the documented CV configuration unless an applicable T, CV5 or AFV rule explicitly imports a provision. See conditional systems. | [Applicability review](conditional-systems.md) |
| [General Requirements](../../rules/section-ev/3-general-requirements.md) | EV chapter reviewed; outside the documented CV configuration unless an applicable T, CV5 or AFV rule explicitly imports a provision. See conditional systems. | [Applicability review](conditional-systems.md) |
| [Tractive System](../../rules/section-ev/4-tractive-system.md) | EV chapter reviewed; outside the documented CV configuration unless an applicable T, CV5 or AFV rule explicitly imports a provision. See conditional systems. | [Applicability review](conditional-systems.md) |
| [Tractive System Energy Storage](../../rules/section-ev/5-tractive-system-energy-storage.md) | EV chapter reviewed; outside the documented CV configuration unless an applicable T, CV5 or AFV rule explicitly imports a provision. See conditional systems. | [Applicability review](conditional-systems.md) |
| [EV Shutdown Circuit and Systems](../../rules/section-ev/6-ev-shutdown-circuit-and-systems.md) | EV chapter reviewed; outside the documented CV configuration unless an applicable T, CV5 or AFV rule explicitly imports a provision. See conditional systems. | [Applicability review](conditional-systems.md) |
| [Chargers](../../rules/section-ev/7-chargers.md) | EV chapter reviewed; outside the documented CV configuration unless an applicable T, CV5 or AFV rule explicitly imports a provision. See conditional systems. | [Applicability review](conditional-systems.md) |
| [Tractive System Accumulator Container Hand Cart](../../rules/section-ev/8-tractive-system-accumulator-container-hand-cart.md) | EV chapter reviewed; outside the documented CV configuration unless an applicable T, CV5 or AFV rule explicitly imports a provision. See conditional systems. | [Applicability review](conditional-systems.md) |
| [Electrical System Form](../../rules/section-ev/9-electrical-system-form.md) | EV chapter reviewed; outside the documented CV configuration unless an applicable T, CV5 or AFV rule explicitly imports a provision. See conditional systems. | [Applicability review](conditional-systems.md) |

---

## AFV

| Source chapter | Review outcome | Compliance entries |
|---|---|---|
| [Alternative Fuel Vehicles](../../rules/section-afv/1-alternative-fuel-vehicles.md) | Conditional alternative-fuel/powertrain entry; confirm final vehicle scope. | [Applicability review](conditional-systems.md) |

---

## IN

| Source chapter | Review outcome | Compliance entries |
|---|---|---|
| [General](../../rules/section-in/1-general.md) | Inspection readiness, evidence access, representative and change control are included; overall inspection administration remains team-wide. | [IN1 — Inspection Readiness and Changes](section-in/in1-general.md) |
| [Motorsport UK Safety Inspection](../../rules/section-in/2-motorsport-uk-safety-inspection.md) | Team-wide safety inspection and equipment pack; electronics prepares relevant systems using the register and IN1 procedure. | Shared/team-owned; see review outcome. |
| [[EV Only] Accumulator Inspection](../../rules/section-in/3-accumulator-inspection.md) | EV-only accumulator inspection; excluded from the documented CV configuration. | [Applicability review](conditional-systems.md) |
| [[EV Only] Electrical Inspection](../../rules/section-in/4-electrical-inspection.md) | EV-only electrical inspection; this does not exempt CV electronics from T/CV rules or the applicable other inspections. | [Applicability review](conditional-systems.md) |
| [Mechanical Inspection](../../rules/section-in/5-mechanical-inspection.md) | LV battery datasheets, relevant rules questions and electronics access tools are included in the mechanical inspection pack. | [IN5 — Mechanical Inspection Evidence](section-in/in5-mechanical.md) |
| [[DV Only] Autonomous System Inspection](../../rules/section-in/6-autonomous-system-inspection.md) | DV-only autonomous inspection/EBS test; conditional on autonomous operation. | [Applicability review](conditional-systems.md) |
| [Tilt Test](../../rules/section-in/7-tilt-test.md) | Battery and electrical fuel-system leakage interfaces are included; whole-vehicle setup and stability remain shared responsibilities. | [IN7 — Tilt Test Interfaces](section-in/in7-tilt.md) |
| [Vehicle Weighing](../../rules/section-in/8-vehicle-weighing.md) | Whole-vehicle weighing; all final electronics must be fitted as part of the ready-to-race configuration. | Shared/team-owned; see review outcome. |
| [[EV Only] Rain Test](../../rules/section-in/9-rain-test.md) | EV-only rain test; excluded from the documented CV configuration, without removing the need for suitable electrical environmental design. | [Applicability review](conditional-systems.md) |
| [Noise Test](../../rules/section-in/10-noise-test.md) | ECU speed, laptop, noise-test support and shutdown demonstrations are included; EV ready-to-drive sound is conditional. | [IN10 — Noise, ECU Speed and Shutdown Tests](section-in/in10-noise-shutdown.md) |
| [Brake Test](../../rules/section-in/11-brake-test.md) | Brake-light observation is included; the hydraulic braking performance test remains brakes-owned. | [IN11 — Brake-Light Inspection](section-in/in11-brake-light.md) |
| [Post Event Inspection](../../rules/section-in/12-post-event-inspection.md) | Electrical retention, safety condition and post-run access are included. EV logger/energy-meter handling is conditional. | [IN12 — Post-Event Electrical Condition](section-in/in12-post-event.md) |
| [Driver Egress Test](../../rules/section-in/13-driver-egress-test.md) | Egress with the final electrical installation is included; driver equipment and inspection prerequisites remain team-wide. | [IN13 — Driver Egress with Electronics Installed](section-in/in13-egress.md) |

---

## S

| Source chapter | Review outcome | Compliance entries |
|---|---|---|
| [Static Event No-Show Penalty](../../rules/section-s/1-static-event-no-show-penalty.md) | Team-wide static-event attendance penalty; no separate electrical-system requirement. | Shared/team-owned; see review outcome. |
| [Business Plan Presentation (BPP) – FS Class and Concept Class](../../rules/section-s/2-business-plan-presentation%28bpp%29-fs-and-concept-class.md) | Business presentation format and logistics; no separate vehicle-electronics requirement. | Shared/team-owned; see review outcome. |
| [Cost and Manufacturing Event – Formula Student Class](../../rules/section-s/3-cost-and-manufacturing-event-fs.md) | Electrical BOM/manufacturing evidence contributions are included; the cost owner retains the complete submission, cost and carbon-accounting requirements. | [S3 — Electronics Cost and Manufacturing Evidence](section-s/cost-manufacturing.md) |
| [Cost and Manufacturing Event – Concept Class](../../rules/section-s/4-cost-and-manufacturing-event-concept.md) | Concept Class cost event; not the working running-CV/FS Class scope. Reassess if the entry class differs. | [Applicability review](conditional-systems.md) |
| [Engineering Design Event – Formula Student Class](../../rules/section-s/5-engineering-design-event-fs.md) | Electrical selection, design justification and EDR evidence contributions are included; team report format and judging requirements remain shared. | [S5 / S7 — Design and Validation Evidence](section-s/design-validation.md) |
| [Engineering Design Event – Concept Class](../../rules/section-s/6-engineering-design-event-concept.md) | Concept Class design event; reassess if the entry class differs. | [Applicability review](conditional-systems.md) |
| [Lap Time Simulation (LTS)](../../rules/section-s/7-lap-time-simulation%28lts%29.md) | Instrumentation contribution to the validation plan is conditional. S7.2.2 states LTS is standalone from the actual vehicle. | [S5 / S7 — Design and Validation Evidence](section-s/design-validation.md) |

---
## D

| Source chapter | Review outcome | Compliance entries |
|---|---|---|
| [Dynamic Events General](../../rules/section-d/1-dynamic-events-general.md) | Staging-area starting support is included; driver allocation and area access are team-wide. | [D — Starting, Restarts and Endurance](section-d/starting-endurance.md) |
| [Driving Rules](../../rules/section-d/2-driving-rules.md) | Independent starting and practice-track approval are included. Driverless start/RES provisions are conditional. | [D — Starting, Restarts and Endurance](section-d/starting-endurance.md) |
| [Weather Conditions](../../rules/section-d/3-weather-conditions.md) | Tyre choices and official weather declarations; no separate CV electronics clause. | Shared/team-owned; see review outcome. |
| [Skidpad Event](../../rules/section-d/4-skidpad-event.md) | Manual skidpad layout/procedure/scoring is driver/team-owned; driverless provisions are conditional. | [Applicability review](conditional-systems.md) |
| [Acceleration Event](../../rules/section-d/5-acceleration-event.md) | Manual acceleration procedure/scoring is driver/team-owned; driverless provisions are conditional. | [Applicability review](conditional-systems.md) |
| [Autocross Event](../../rules/section-d/6-autocross-event.md) | Manual autocross procedure/scoring is driver/team-owned; driverless sensor/data restrictions are conditional. | [Applicability review](conditional-systems.md) |
| [Endurance and Efficiency Event](../../rules/section-d/7-endurance-and-efficiency-event.md) | Power-down, driver-change and restart requirements are included. Course, fuel measurement and scoring remain team-wide; hybrid energy matters are conditional. | [D — Starting, Restarts and Endurance](section-d/starting-endurance.md) |
| [[DV Only] Trackdrive Event](../../rules/section-d/8-trackdrive-event.md) | DV-only trackdrive; conditional on autonomous operation. | [Applicability review](conditional-systems.md) |
| [Dynamic Events Penalties](../../rules/section-d/9-dynamic-events-penalties.md) | Unaided restart consequence is included. Other driving/scoring penalties remain team-wide; EV power/voltage penalties are conditional. | [D — Starting, Restarts and Endurance](section-d/starting-endurance.md) |
