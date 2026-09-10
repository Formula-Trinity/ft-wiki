<h1>Injector Flow Rate</h1>

<h2>Overview</h2>

<p>
  Injector flow rate describes the amount of fuel that an injector can deliver
  over a given period while it is fully open. It is commonly specified in:
</p>

<ul>
  <li><strong>cc/min</strong> — cubic centimetres of fuel delivered per minute</li>
  <li><strong>g/min</strong> or <strong>kg/h</strong> — mass of fuel delivered over time</li>
  <li><strong>lb/h</strong> — commonly used in American specifications</li>
</ul>

<p>
  For example, a <strong>250 cc/min injector</strong> can theoretically deliver
  250 cm<sup>3</sup> of fuel per minute when held continuously open under its
  specified test conditions. Because volumetric flow depends on the fuel's
  density, the test fuel and operating conditions should be considered when
  comparing injector ratings.
</p>

<h2>Factors Affecting Flow Rate</h2>

<p>
  The amount of fuel delivered by an injector depends on several factors:
</p>

<ul>
  <li>
    <strong>Injector size:</strong> A larger nozzle and valve opening generally
    permit a greater flow rate.
  </li>
  <li>
    <strong>Fuel-pressure difference:</strong> Flow depends on the pressure
    difference across the injector, rather than fuel-rail pressure alone.
  </li>
  <li>
    <strong>Fuel properties:</strong> Fuel density and viscosity affect
    volumetric and mass flow.
  </li>
  <li>
    <strong>Pulse width:</strong> The ECU controls how long the injector is
    commanded to remain open during each injection event.
  </li>
  <li>
    <strong>Injector dead time:</strong> The injector requires a short time to
    open after the ECU energises it. Battery voltage, fuel pressure and injector
    design can affect this delay.
  </li>
</ul>

<p>
  For a port fuel injector, the pressure difference across the injector is
  approximately:
</p>

<p>
  <strong>
    &Delta;P =
    P<sub>fuel rail</sub> &minus;
    P<sub>intake manifold</sub>
  </strong>
</p>

<p>
  A fuel-pressure regulator is used to control this pressure difference. In a
  manifold-referenced system, the regulator changes rail pressure with manifold
  pressure so that the pressure difference across the injector remains
  approximately constant.
</p>

<h2>Effect of Fuel Pressure</h2>

<p>
  For the same injector and fuel, flow rate changes approximately with the
  square root of the pressure ratio:
</p>

<p>
  <strong>
    Q<sub>2</sub> =
    Q<sub>1</sub> &times;
    sqrt(&Delta;P<sub>2</sub> / &Delta;P<sub>1</sub>)
  </strong>
</p>

<p>where:</p>

<ul>
  <li>
    Q<sub>1</sub> is the known flow rate at pressure difference
    &Delta;P<sub>1</sub>.
  </li>
  <li>
    Q<sub>2</sub> is the estimated flow rate at pressure difference
    &Delta;P<sub>2</sub>.
  </li>
</ul>

<p>
  For example, if a 250 cc/min injector is rated at a pressure difference of
  3 bar and the pressure difference is increased to 4 bar:
</p>

<p>
  <strong>
    Q<sub>2</sub> =
    250 &times; sqrt(4 / 3)
    &asymp; 289 cc/min
  </strong>
</p>

<p>
  Increasing fuel pressure therefore increases injector flow, but the
  relationship is not directly proportional. In this example, increasing the
  pressure difference by approximately 33% increases the flow rate by only
  approximately 15%.
</p>

<h2>Flow Rate and Pulse Width</h2>

<p>
  The rated flow rate describes how quickly an injector can deliver fuel.
  During normal engine operation, however, the ECU opens the injector for only
  a few milliseconds at a time. This commanded opening duration is called the
  <strong>injector pulse width</strong>.
</p>

<p>
  Ignoring transient effects, the fuel mass delivered during an injection event
  can be approximated by:
</p>

<p>
  <strong>
    m<sub>fuel</sub> &asymp;
    ṁ<sub>injector</sub> &times;
    t<sub>effective</sub>
  </strong>
</p>

<p>where:</p>

<ul>
  <li>
    m<sub>fuel</sub> is the mass of fuel delivered.
  </li>
  <li>
    ṁ<sub>injector</sub> is the injector's mass flow rate.
  </li>
  <li>
    t<sub>effective</sub> is the effective time for which fuel flows.
  </li>
</ul>

<p>
  The effective flow time is not always identical to the commanded pulse width
  because the injector takes time to open and close. The ECU compensates for
  this behaviour using injector calibration data, including injector dead time.
</p>

<p>
  As a simplified example, if an injector flows at 4 g/s and effectively flows
  for 3 ms:
</p>

<p>
  <strong>
    m<sub>fuel</sub> =
    4 g/s &times; 0.003 s =
    0.012 g
  </strong>
</p>

<p>
  The ECU can therefore increase the amount of injected fuel by increasing the
  pulse width, provided that the injector still has sufficient time available
  to open and close correctly.
</p>

<h2>Injector Duty Cycle</h2>

<p>
  Injector duty cycle is the percentage of the available injection period for
  which the injector is commanded open:
</p>

<p>
  <strong>
    Duty cycle =
    (pulse width / available period) &times; 100%
  </strong>
</p>

<p>
  For a four-stroke engine using one injection event per cylinder every engine
  cycle, the available period is the time required for two crankshaft
  revolutions. The exact calculation may differ when multiple injection events
  are used.
</p>

<p>
  Injectors are normally selected with spare flow capacity rather than being
  operated continuously at 100% duty cycle. If the required pulse width becomes
  too long, the injector can reach its maximum usable delivery rate. It may then
  be unable to provide the required fuel, potentially causing the engine to run
  lean.
</p>

<h2>Relationship to Air–Fuel Ratio</h2>

<p>
  The required injector flow is determined by the amount of air entering the
  engine and the target air–fuel ratio (AFR):
</p>

<p>
  <strong>
    m<sub>fuel</sub> =
    m<sub>air</sub> / target AFR
  </strong>
</p>

<p>
  The ECU estimates or measures the incoming air, selects a target AFR from its
  calibration maps, and calculates the required fuel mass. It then uses the
  injector's calibrated flow characteristics to convert this fuel requirement
  into a pulse width.
</p>

<p>The overall process can be summarised as:</p>

<ol>
  <li>The ECU determines the mass of air entering the cylinder.</li>
  <li>It selects the target AFR for the current operating conditions.</li>
  <li>It calculates the required fuel mass.</li>
  <li>It determines the required injector pulse width.</li>
  <li>
    It applies corrections for factors such as injector dead time, battery
    voltage, fuel pressure and temperature.
  </li>
</ol>

<p>
  Injector flow rate therefore specifies how quickly fuel can be supplied,
  while pulse width determines how much fuel is delivered during each injection
  event.
</p>