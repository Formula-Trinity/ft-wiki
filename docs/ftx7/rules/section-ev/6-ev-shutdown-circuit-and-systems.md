# EV Shutdown Circuit and Systems

### EV6.1 Shutdown Circuit

##### EV6.1.1

> The shutdown circuit directly carries the power driving the AIRs, see EV5.6, and the pre-
> charge circuitry, see EV5.7.

##### EV6.1.2

> The shutdown circuit is defined as a series connection of at least two master switches,
> three shutdown buttons, the BOTS, see T6.2, the IMD, the inertia switch, see T11.5, the
> BSPD, see T11.6, all required interlocks and the AMS.
>
> An explanatory schematic of the required shutdown circuit, excluding any possible
> interlock circuitry, is shown in Figure 29.

<div style="height: 419px;" aria-hidden="true"></div>

<small><em>Figure 29: Explanatory example schematic of the required shutdown circuit.</em></small>

> Elements marked ** are only required for ADS.
> Elements marked * are required in accordance with the associated rule(s).

##### EV6.1.3

> All parts of the shutdown circuit defined in EV6.1.2 must be on the high-side connection
> of the AIR coils and the pre-charge circuitry.

##### EV6.1.4

> The Tractive System Master Switch (TSMS), see EV6.2, must be the last switch before the
> AIRs except for pre-charge circuitry and hardwired interlocks.
>
> NOTE:  Whilst hardwired interlocks may be located after the TSMS, it is good practice for
> them to be before the TSMS

##### EV6.1.5

> If the shutdown circuit is opened, the TS must be shutdown by opening all AIRs and the
> pre-charge relay. The voltage in the TS must drop to below 60VDC and 25VACRMS in less
> than five seconds. All TS accumulator current flow must stop immediately.
>
> The action of opening the AIRs may be delayed by ≤250ms to signal the action to the
> motor controllers and reduce the TS current before the AIRs are opened. The AIR supply
> must be abruptly switched off before reaching the minimum AIR supply voltage.

##### EV6.1.6

> If the shutdown circuit is opened by the AMS or the IMD, it has to be latched open by a
> non-programmable logic that can only be manually reset by a person at the vehicle who is
> not the driver.

##### EV6.1.7

> All circuits that are part of the shutdown circuit must be designed in a way, that in the de-
> energized/disconnected state they open the shutdown circuit.

##### EV6.1.8

> It must be possible to demonstrate that all features of the shutdown circuit function
> correctly. This includes all interlocks.

##### EV6.1.9

> Every system that is required to or is able to open the shutdown circuit must have its own,
> non-programmable, power stage to achieve this. The respective power stages must be
> designed to be able to carry the shutdown circuit current, e.g. AIR inrush currents, and
> such that a failure cannot result in electrical power being fed back into the electrical
> shutdown circuit.

##### EV6.1.10

> The shutdown buttons, the BOTS, the TSMS and all interlocks must not act through any
> power stage.

##### EV6.1.11

> All signals influencing the shutdown circuit are SCSs, see T11.9.

### EV6.2 Tractive System Master Switch

##### EV6.2.1

> An TSMS according to T11.2 must be part of the shutdown circuit, see EV6.1.2.

##### EV6.2.2

> The TSMS must be fitted with a “lockout/tagout” capability to prevent accidental
> activation of the TS. The ESO must ensure that it is locked in the off position whenever
> work is done on the vehicle or no ESO is present.

##### EV6.2.3

> The TSMS must be mounted in the middle of a completely orange circular area of ≥50mm
> diameter placed on a high contrast background.

##### EV6.2.4

> The TSMS must be marked with “TS” and a symbol according to “ISO 7010-W012”
> (triangle with black lightning bolt on yellow background).

### EV6.3 Insulation Monitoring Device

##### EV6.3.1

> Every vehicle must have an IMD installed in the TS system.

##### EV6.3.2

> The IMD must be a Bender A-ISOMETER® iso-F1 IR155-3203 or -3204, -4203, or -4204, or a
> Bender ISOMETER® iso165C-1, iso175, or equivalent IMD approved for automotive use.
> Equivalency may be approved by the officials based on the following criteria: robustness
> to vibration, operating temperature range, IP rating, availability of a direct output, a self-
> test facility and must not be powered by the system which is monitored.

##### EV6.3.3

> The response value of the IMD must be set to ≥500 Ω/V, related to the maximum TS
> voltage.

##### EV6.3.4

> The IMD response value must not be changed after electrical inspection.

##### EV6.3.5

> The IMD must be connected on the vehicle side of the AIRs.

##### EV6.3.6

> One IMD chassis ground measurement line must be connected to the grounded TSAC.
> The other chassis ground measurement line must be connected to the main hoop. Each
> connection must use a separate conductor, rated for at least maximum TS voltage. An
> open circuit in any of this ground measurement connections must result in an opened
> shutdown circuit.

##### EV6.3.7

> In case of an insulation failure or an IMD failure, the IMD must open the shutdown circuit.
> This must be done without the influence of any programmable logic. See also EV6.1.6
> regarding the re-activation of the TS after an insulation fault.

##### EV6.3.8

> A red indicator light in the cockpit, that is easily visible from inside and outside the cockpit
> in bright sunlight and clearly marked with the lettering “IMD”, must light up if the IMD
> opens the shutdown circuit. It must stay illuminated until the error state has been
> manually reset, see EV6.1.6. Signals controlling this indicator are SCS, see T11.9.
