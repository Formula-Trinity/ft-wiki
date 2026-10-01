# Injector Flow Rate

## Overview

Injector flow rate describes the amount of fuel that an injector can deliver over a given period while it is fully open. It is commonly specified in:

- **cc/min** — cubic centimetres of fuel delivered per minute
- **g/min** or **kg/h** — mass of fuel delivered over time
- **lb/h** — commonly used in American specifications

For example, a **250 cc/min injector** can theoretically deliver 250 cm³ of fuel per minute when held continuously open under its specified test conditions. Because volumetric flow depends on the fuel's density, the test fuel and operating conditions should be considered when comparing injector ratings.

## Factors Affecting Flow Rate

The amount of fuel delivered by an injector depends on several factors:

- **Injector size:** A larger nozzle and valve opening generally permit a greater flow rate.
- **Fuel-pressure difference:** Flow depends on the pressure difference across the injector, rather than fuel-rail pressure alone.
- **Fuel properties:** Fuel density and viscosity affect volumetric and mass flow.
- **Pulse width:** The ECU controls how long the injector is commanded to remain open during each injection event.
- **Injector dead time:** The injector requires a short time to open after the ECU energises it. Battery voltage, fuel pressure and injector design can affect this delay.

For a port fuel injector, the pressure difference across the injector is approximately:

$$
\Delta P = P_{\text{fuel rail}} - P_{\text{intake manifold}}
$$

A fuel-pressure regulator is used to control this pressure difference. In a manifold-referenced system, the regulator changes rail pressure with manifold pressure so that the pressure difference across the injector remains approximately constant.

## Effect of Fuel Pressure

For the same injector and fuel, flow rate changes approximately with the square root of the pressure ratio:

$$
Q_2 = Q_1 \sqrt{\frac{\Delta P_2}{\Delta P_1}}
$$

where:

- $Q_1$ is the known flow rate at pressure difference $\Delta P_1$.
- $Q_2$ is the estimated flow rate at pressure difference $\Delta P_2$.

For example, if a 250 cc/min injector is rated at a pressure difference of 3 bar and the pressure difference is increased to 4 bar:

$$
Q_2 = 250\sqrt{\frac{4}{3}} \approx 289\ \text{cc/min}
$$

Increasing fuel pressure therefore increases injector flow, but the relationship is not directly proportional. In this example, increasing the pressure difference by approximately 33% increases the flow rate by only approximately 15%.

## Flow Rate and Pulse Width

The rated flow rate describes how quickly an injector can deliver fuel. During normal engine operation, however, the ECU opens the injector for only a few milliseconds at a time. This commanded opening duration is called the **injector pulse width**.

Ignoring transient effects, the fuel mass delivered during an injection event can be approximated by:

$$
m_{\text{fuel}} \approx \dot{m}_{\text{injector}} \times t_{\text{effective}}
$$

where:

- $m_{\text{fuel}}$ is the mass of fuel delivered.
- $\dot{m}_{\text{injector}}$ is the injector's mass flow rate.
- $t_{\text{effective}}$ is the effective time for which fuel flows.

The effective flow time is not always identical to the commanded pulse width because the injector takes time to open and close. The ECU compensates for this behaviour using injector calibration data, including injector dead time.

As a simplified example, if an injector flows at 4 g/s and effectively flows for 3 ms:

$$
m_{\text{fuel}} = 4\ \text{g/s} \times 0.003\ \text{s} = 0.012\ \text{g}
$$

The ECU can therefore increase the amount of injected fuel by increasing the pulse width, provided that the injector still has sufficient time available to open and close correctly.

## Injector Duty Cycle

Injector duty cycle is the percentage of the available injection period for which the injector is commanded open:

$$
\text{Duty cycle} =
\frac{\text{pulse width}}{\text{available period}} \times 100\%
$$

For a four-stroke engine using one injection event per cylinder every engine cycle, the available period is the time required for two crankshaft revolutions. The exact calculation may differ when multiple injection events are used.

Injectors are normally selected with spare flow capacity rather than being operated continuously at 100% duty cycle. If the required pulse width becomes too long, the injector can reach its maximum usable delivery rate. It may then be unable to provide the required fuel, potentially causing the engine to run lean.

## Relationship to Air–Fuel Ratio

The required injector flow is determined by the amount of air entering the engine and the target air–fuel ratio (AFR):

$$
m_{\text{fuel}} = \frac{m_{\text{air}}}{\text{target AFR}}
$$

The ECU estimates or measures the incoming air, selects a target AFR from its calibration maps, and calculates the required fuel mass. It then uses the injector's calibrated flow characteristics to convert this fuel requirement into a pulse width.

The overall process can be summarised as:

1. The ECU determines the mass of air entering the cylinder.
2. It selects the target AFR for the current operating conditions.
3. It calculates the required fuel mass.
4. It determines the required injector pulse width.
5. It applies corrections for factors such as injector dead time, battery voltage, fuel pressure and temperature.

Injector flow rate therefore specifies how quickly fuel can be supplied, while pulse width determines how much fuel is delivered during each injection event.