<h1>Injection Timing</h1>

<h3>Engine-Position Sensing</h3>

<p>
  To determine the correct injection timing, the ECU must know:
</p>

<ul>
  <li>The engine speed</li>
  <li>The crankshaft position</li>
  <li>The current stage of the four-stroke cycle</li>
</ul>

<h4>Crankshaft Sensor</h4>

<p align="center">
  <img
    src="../images/crankshaft.jpg"
    alt="Crankshift"
    width="600"
  >
</p>

<p align="center">
  <em>Figure 4: Crankshaft.</em>
</p>

<p>
  The ECU uses a variable-reluctance (VR) sensor positioned near the crankshaft.
  This sensor detects the teeth of a rotating trigger wheel, allowing the ECU
  to calculate the crankshaft angle and engine speed.
</p>

<h4>Camshaft Sensor</h4>

<p>
  The crankshaft completes two revolutions during each four-stroke engine
  cycle. Crankshaft position alone therefore does not identify which stroke a
  cylinder is currently completing.
</p>

<p>
  A second VR sensor positioned near the camshaft provides a cylinder-phase
  reference. This allows the ECU to determine the current stroke of cylinder 1
  and operate the injectors at the correct point in the engine cycle.
</p>

<p>
  <em>
    Further information about the crankshaft and camshaft sensors is available
    on the relevant sensor pages of this wiki.
  </em>
</p>