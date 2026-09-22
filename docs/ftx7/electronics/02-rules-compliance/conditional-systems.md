# Conditional and Excluded Systems

[Rules and Compliance](index.md)

Applicability follows the [documented FTX7 configuration](../index.md): combustion engine, 12 V lead-acid supply and mechanical throttle. Hybrid, autonomous, alternative-fuel and optional-equipment absence is a working scope assumption where the overview is silent; confirm the final build.

Record each configuration decision against the linked source rules. Add compliance and evidence entries when a system is included in the FTX7 build.

## Electronic throttle and APPS

**Rule:** [T11.8.1](../../rules/section-t/11-electrical-components.md#t1181); [CV1.6.1](../../rules/section-cv/1-internal-combustion-engine-powertrains.md#cv161)

The overview explicitly states mechanical throttle. Confirm this in the final build; review [T11.8](../../rules/section-t/11-electrical-components.md#t118-accelerator-pedal-position-sensor-apps) and [CV1.6](../../rules/section-cv/1-internal-combustion-engine-powertrains.md#cv16-electronic-throttle-control) if the configuration changes.

**Configuration confirmation:** Pending — record the fitted configuration, reviewer and date.

## LV hybrid

**Rule:** [CV5.1.1](../../rules/section-cv/5-lv-hybrid-system.md#cv511); [CV5.3.3](../../rules/section-cv/5-lv-hybrid-system.md#cv533)

No propulsion motor or hybrid storage container is described. Confirm the final powertrain configuration against [CV5](../../rules/section-cv/5-lv-hybrid-system.md), [T11.7.8](../../rules/section-t/11-electrical-components.md#t1178) and [T12.1.5](../../rules/section-t/12-vehicle-identification.md#t1215).

**Configuration confirmation:** Pending — record the fitted configuration, reviewer and date.

## Other battery chemistries

**Rule:** [T11.7.7](../../rules/section-t/11-electrical-components.md#t1177); [T11.7.8](../../rules/section-t/11-electrical-components.md#t1178)

The main battery is documented as lead-acid. Confirm the chemistry of every fitted battery, including auxiliaries, against the linked rules. Record the installation evidence in the [battery compliance page](section-t/t11-electrical/lv-battery.md).

**Configuration confirmation:** Pending — record the fitted configuration, reviewer and date.

## Electric powertrain

**Rule:** [EV1.1.1](../../rules/section-ev/1-definitions.md#ev111); [EV9.1.3](../../rules/section-ev/9-electrical-system-form.md#ev913)

No electric tractive system is described. Confirm the final configuration and record any applicable EV references using the [EV source chapter links](scope-and-coverage.md#ev).

**Configuration confirmation:** Pending — record the fitted configuration, reviewer and date.

## Autonomous operation

**Rule:** [T14.1.1](../../rules/section-t/14-autonomous-system.md#t1411); [T15.4.5](../../rules/section-t/15-autonomous-system-brake.md#t1545)

No autonomous driving system is described. Confirm manual-only operation against [T14](../../rules/section-t/14-autonomous-system.md), [T15](../../rules/section-t/15-autonomous-system-brake.md), [CV1.2](../../rules/section-cv/1-internal-combustion-engine-powertrains.md#cv12-starter) and [IN6](../../rules/section-in/6-autonomous-system-inspection.md).

**Configuration confirmation:** Pending — record the fitted configuration, reviewer and date.

## Compressed gas or high-pressure hydraulics

**Rule:** [T9.1.1](../../rules/section-t/9-critical-fasteners.md#t911); [T9.4.1](../../rules/section-t/9-critical-fasteners.md#t941)

No pneumatic/hydraulic actuation package is described in the electronics overview. Confirm any gearshift or other actuator package with its owner and record applicability against [T9](../../rules/section-t/9-critical-fasteners.md).

**Configuration confirmation:** Pending — record the fitted configuration, reviewer and date.

## Gaseous fuel or alternative powertrain

**Rule:** [T9.5.1](../../rules/section-t/9-critical-fasteners.md#t951); [AFV1.1.2](../../rules/section-afv/1-alternative-fuel-vehicles.md#afv112)

No gaseous fuel or alternative powertrain is described. Confirm the final fuel/powertrain configuration against [AFV](../../rules/section-afv/1-alternative-fuel-vehicles.md) and [T9.5](../../rules/section-t/9-critical-fasteners.md#t95-gaseous-fuel-systems).

**Configuration confirmation:** Pending — record the fitted configuration, reviewer and date.

## Optional sensors, cameras and actuators

**Rule:** [T11.11.4](../../rules/section-t/11-electrical-components.md#t11114); [T13.5.1](../../rules/section-t/13-vehicle-and-driver-equipment.md#t1351)

Antenna exceptions, cameras, front sensors, active aero, rear steering and active exhaust controls have conditional entries in their relevant pages. Close each with actual fitment evidence; silence in a component template does not prove that a device is absent.

**Configuration confirmation:** Pending — record the fitted configuration, reviewer and date.

## EV/DV inspection and staffing

**Rule:** [IN3.1.1](../../rules/section-in/3-accumulator-inspection.md#in311); [IN6.1.1](../../rules/section-in/6-autonomous-system-inspection.md#in611)

Record the inspection and staffing scope for the confirmed vehicle configuration using [A4](../../rules/section-a/4-general-req.md), [A6](../../rules/section-a/6-general-rules.md), [IN3](../../rules/section-in/3-accumulator-inspection.md), [IN4](../../rules/section-in/4-electrical-inspection.md), [IN6](../../rules/section-in/6-autonomous-system-inspection.md) and [IN9](../../rules/section-in/9-rain-test.md).

**Configuration confirmation:** Pending — record the fitted configuration, reviewer and date.

## Missing event-specific detail

The FTX7 CCBOM scope and CV submission route remain open. Record the applicable event documents or clarification alongside [S3.5.2](../../rules/section-s/3-cost-and-manufacturing-event-fs.md#s352) and [T11.9.7](../../rules/section-t/11-electrical-components.md#t1197).

[Review of every rules chapter](scope-and-coverage.md)
