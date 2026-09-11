# Intake

## Function of the Intake System

The function of the intake system is to supply the engine with clean, controlled, and evenly
distributed air. Air enters the system through the air filter, passes through the throttle body and
restrictor, expands into the plenum, and is then directed through the runners into the engine
cylinders. On Bruce, the intake system is especially important because the Honda CBR600RR
engine is being used in a Formula Student application, where throttle response, drivability,
packaging, reliability, and rules compliance are all critical.

For a naturally aspirated Formula Student engine, the intake system must do more than simply
connect the air filter to the cylinder head. It must minimise unnecessary pressure losses, maintain
stable airflow, reduce turbulence where possible, and distribute air as evenly as possible between
all four cylinders. Uneven airflow distribution can cause differences in cylinder filling, which may
affect air-fuel ratio consistency, combustion quality, engine mapping, and overall performance.
The intake must also fit within the available chassis and bodywork space while remaining strong
enough to withstand vibration, engine movement, and repeated assembly or removal.

The restrictor is one of the most important parts of the system because it limits the maximum
airflow available to the engine. Since this restriction is required by the Formula Student rules,
the rest of the intake must be designed to make the best use of the available air. This means
avoiding unnecessary sharp corners, sudden changes in cross-sectional area, poor sealing surfaces,
or rough internal features that could add further losses after the restrictor. A well-designed
intake cannot remove the effect of the restrictor, but it can help reduce additional losses and
improve pressure recovery downstream of it.

The plenum acts as an air reservoir between the restrictor and the runners. Its purpose is to
provide a more stable air supply to the cylinders, especially because each cylinder draws air in
pulses rather than as a continuous flow. The volume and shape of the plenum influence pressure
stability, pressure-wave behaviour, throttle response, and cylinder-to-cylinder distribution. A
smoother and more rounded plenum shape is preferred because it helps reduce flow separation
and avoids the sharp internal corners that can occur in simpler fabricated box-style designs.

The runners guide the air from the plenum into the engine ports. Their length, diameter, entry
shape, and alignment affect airflow velocity, pressure-wave tuning, and the quality of flow entering
each cylinder. In the final intake design, short runners were used to suit the packaging around
the engine and chassis while keeping the air path compact and direct. The runner entrances
and internal surfaces should be kept as smooth and consistent as possible so that each cylinder
receives a similar air supply.

Overall, the intake system has a direct influence on engine breathing, throttle response, mapping
consistency, reliability, and serviceability. For this reason, the final design for Bruce uses a
carbon fibre plenum, a bought restrictor, the original motorcycle throttle body with only minor
modifications, and short runners to create a lightweight, compact, and practical intake system
suitable for Formula Student use.

## Science Behind an Intake System

The intake system operates as a combination of fluid dynamics, pressure-wave behaviour, com
bustion demand, and packaging design. Although it may appear to be a simple path for air to
enter the engine, the intake has a direct effect on how efficiently each cylinder is filled. For a
naturally aspirated engine, there is no compressor forcing air into the cylinders, so the engine
relies on atmospheric pressure, piston motion, intake geometry, and pressure-wave effects to draw
air into the combustion chamber.

During the intake stroke, the piston moves down the cylinder while the intake valves are open.
This creates a pressure difference between the cylinder and the intake system, causing air to flow
through the air filter, throttle body, restrictor, plenum, runners, and intake ports. The easier
it is for air to move through this path, the more effectively the cylinder can be filled. This is
commonly described using volumetric efficiency, which is the ratio between the actual amount of
air inducted into the cylinder and the theoretical maximum amount the cylinder could hold at
atmospheric conditions.

For a four-stroke engine, each cylinder only completes one intake event every two crankshaft
revolutions. This means that the airflow into the engine is not steady. Instead, the runners and
plenum experience a series of pulsed flow demands as each cylinder opens and closes its intake
valves. The intake system must therefore supply air smoothly despite the fact that each cylinder
draws air intermittently. This is one of the main reasons why the plenum is required.

The basic air demand of the engine can be related to engine displacement, engine speed, and
volumetric efficiency. A simplified expression for the engine volume flow rate is:

<img width="132" height="62" alt="image" src="https://github.com/user-attachments/assets/b1e59a13-4f4b-45b3-8be7-e5307a5ccc3c" />

Where 
<img width="35" height="35" alt="image" src="https://github.com/user-attachments/assets/3a88f3c9-2123-4fa3-a3d9-6f0ef06d2ca0" />
is the intake volume flow rate, <img width="26" height="27" alt="image" src="https://github.com/user-attachments/assets/94c1a3db-b073-4f75-aeae-52c1eefad162" /> is the total engine displacement, N is the engine speed in revolutions per second, and <img width="21" height="20" alt="image" src="https://github.com/user-attachments/assets/12aa3f27-b00d-462f-b915-69c3dd43968b" /> is the volumetric efficiency. The division by two is required
because a four-stroke engine only has one intake stroke every two revolutions. This equation
shows why intake flow demand increases strongly with engine speed, and why a high-revving
motorcycle engine such as the Honda CBR600RR requires careful intake design when used in a
Formula Student car.

The restrictor is the main flow-limiting component in the Formula Student intake system. Since
all of the engine air must pass through a small restrictor throat, the air velocity through this
region becomes high, especially at large throttle openings and high engine speeds. According to
the continuity relationship,

<img width="86" height="20" alt="image" src="https://github.com/user-attachments/assets/2f768573-a100-485b-9b32-b81d6467b4a7" />

where <img width="21" height="17" alt="image" src="https://github.com/user-attachments/assets/115f1244-6e3f-4655-8c1c-14f48319bc1a" /> is mass flow rate, <img width="16" height="20" alt="image" src="https://github.com/user-attachments/assets/27149750-cfc9-481f-9809-4be72b46b783" /> is air density, A is cross-sectional area, and v is flow velocity. For a
given engine air demand, reducing the flow area increases the velocity through the restrictor. High
velocity through the restrictor increases pressure loss, meaning that the pressure downstream of
the restrictor can be lower than atmospheric pressure. Because of this, the rest of the intake
system must avoid adding unnecessary extra losses.

Pressure losses occur when the airflow passes through sharp corners, sudden expansions, rough
surfaces, steps, poorly matched joints, or abrupt changes in direction. These losses can be
represented generally as:

<img width="116" height="47" alt="image" src="https://github.com/user-attachments/assets/53042eda-7893-43c2-949f-158c60df009a" />

where <img width="31" height="22" alt="image" src="https://github.com/user-attachments/assets/d5569432-469b-4780-a73c-ff6b1048074c" /> is the pressure loss and K is a loss coefficient based on the geometry. This shows
that losses increase with the square of velocity, making the high-speed flow region around the
restrictor especially important. A small design issue near the restrictor can therefore have a large
effect on the pressure available to the engine.

The plenum is positioned downstream of the restrictor and upstream of the runners. Its purpose
is to act as an air reservoir between the single restrictor inlet and the four individual cylinder
runners. It can be thought of as a capacitor for airflow: it helps smooth the pressure pulses
caused by the individual intake events and provides a more stable air supply to each runner. If
the plenum is too small, pressure fluctuations may become large and the cylinders may compete
more strongly for air. If the plenum is too large, throttle response can become slower because a
larger volume of air must be filled or emptied when the throttle position changes. Therefore,
plenum volume is always a compromise between pressure stability, throttle response, packaging,
and manufacturability.

The shape of the plenum is also important. A plenum with sharp internal corners or sudden
changes in section can cause flow separation and turbulence. This can reduce pressure recovery
after the restrictor and may cause uneven flow distribution between cylinders. A smoother, more
rounded plenum shape is generally preferred because it helps the air expand more gradually after
the restrictor and reduces the chance of stagnant regions or separated flow. This was one of the
reasons why the final intake concept moved away from a simple angular box-style plenum and
towards a rounded carbon fibre design.

The runners guide air from the plenum into the engine ports. Their length, diameter, curvature,
entry shape, and alignment influence both airflow velocity and pressure-wave tuning. When an
intake valve opens, a low-pressure wave travels up the runner. When this wave reaches a change
in area, such as the runner entrance or the plenum, part of the wave is reflected back toward
the cylinder. If the reflected wave returns to the intake valve at the correct time, it can help
increase the pressure near the valve as the cylinder is filling. This can improve cylinder filling
over a certain engine speed range.

Runner length strongly affects the timing of these pressure waves. Longer runners generally tune
the intake for lower engine speeds, while shorter runners generally favour higher engine speeds.
This is because the pressure wave takes longer to travel along a longer runner and return to the
intake valve. However, the ideal runner length is not decided by theory alone. It also depends
on the target rpm range, intake valve timing, port length inside the cylinder head, available
packaging space, restrictor behaviour, and the plenum shape. For the Honda CBR600RR package
on Bruce, the earlier intake calculation work suggested that a runner length of roughly 10–12.5
cm was a sensible starting point once the intake path inside the cylinder head was considered.

Runner diameter is also important. If the runners are too small, they can restrict flow at high
engine speed and increase pressure losses. If they are too large, the air velocity can become
too low, reducing the strength of the intake pressure waves and potentially weakening throttle
response. The runner entries should also be smooth and consistent. Sharp runner entrances,
internal resin edges, poor alignment, or large differences between runners can cause uneven airflow
distribution between cylinders. This may affect fuelling, combustion quality, engine mapping,
and reliability.

Air temperature is another factor in intake performance. Cooler air is denser, which means a
greater mass of air can enter the cylinder for the same volume. If the intake absorbs too much
heat from the engine bay, the density of the intake charge decreases and the potential engine
output is reduced. This is one advantage of using carbon fibre for the plenum. Carbon fibre
composite has lower thermal conductivity than aluminium, so it can help reduce heat transfer
into the intake air. However, the main performance drivers of an intake system are still geometry,
sealing, and tuning rather than material alone.

Sealing is critical because any air leak downstream of the throttle or restrictor can allow unmetered
air into the engine. This can make the air-fuel ratio inconsistent, disturb idle quality, and make
engine mapping more difficult. Leaks at the restrictor, plenum flange, runner joints, or throttle
body interface can therefore reduce both performance and reliability. For this reason, the intake
interfaces must use repeatable sealing surfaces, suitable gasket material, controlled fastener
tightening, and careful inspection after assembly.

Overall, the science behind the intake system is based on controlling airflow, pressure loss,
pressure-wave behaviour, temperature, and cylinder-to-cylinder distribution. A good Formula
Student intake should make the best use of the limited airflow available through the restrictor,
recover pressure efficiently after the restrictor, provide a stable plenum volume, guide air smoothly
into each runner, and remain reliable under vibration, heat, and repeated assembly. The final
design for Bruce is therefore a compromise between theoretical intake performance, packaging,
manufacturability, material choice, serviceability, and validation practicality.

## Design Constraints and FSUK Requirements

The intake system for Bruce must be designed around both performance requirements and
Formula Student UK scrutineering requirements. While the intake geometry affects pressure loss,
throttle response, pressure recovery, cylinder filling, and airflow distribution, the first requirement
is that the system is compliant, safe, reliable, and inspectable. For this reason, the intake was
treated as a rules-constrained engineering component rather than only a performance part.

For FSUK 2026, the intake system is mainly governed by the internal combustion vehicle rules
under CV1.3, CV1.4, CV1.5, and CV1.7. Rule CV1.3 states that all parts of the engine air and
fuel control systems, including the throttle, complete air intake system, air filter, and any air
boxes, must lie within the surface envelope of the car. This means that the air filter, throttle
body, restrictor, plenum, and runners must all be packaged within the permitted vehicle envelope
and checked against the chassis, bodywork, driver area, and surrounding systems.

The intake must also be protected from impact where required. Any part of the intake system
less than 350 mm above the ground must be protected from impacts. This is relevant because the
intake system sits close to the engine and surrounding chassis structure, and any low-mounted or
exposed intake component must not be vulnerable to damage during running, scrutineering, or
handling.

The intake manifold must be securely attached to the engine block or cylinder head using brackets
and mechanical fasteners. The rules also state that rubber bushings or hoses are not considered
a secure attachment method for the intake manifold. Therefore, the final intake must not rely
only on flexible connections for structural support. Any significant intake mass or cantilevered
section must be supported so that vibration, engine movement, and chassis flex do not damage
the plenum, runners, throttle body, or cylinder head. If a support is attached to the chassis,
isolation must be included to allow for engine movement.

The intake system must include an air filter at the entry to protect the engine from dirt and debris.
This is important for reliability, as unfiltered air could damage the engine or contaminate the
throttle body and intake runners (Look at Bella’s old engine). The final packaging must therefore
allow the air filter to be installed securely without obstructing throttle operation, restricting
airflow unnecessarily, or interfering with nearby components.

The throttle system is another key constraint. The vehicle must be equipped with a throttle
body, and the throttle may be mechanically actuated by a cable or rod system, or controlled
by an electronic throttle system if the relevant ETC rules are satisfied. For the final intake
design, the original Honda CBR600RR motorcycle throttle body was retained with only minor
modifications. This reduced design risk because the throttle body is already compatible with the
engine and its sensors. The throttle mechanism must move smoothly, must not bind or stick,
and must be protected from debris ingress. If a mechanical throttle cable is used, it must be
routed away from exhaust heat and must not be bent, kinked, or overstressed.

The restrictor is the main Formula Student performance constraint on the intake system. For
a naturally aspirated gasoline engine, a single circular restrictor with a maximum diameter
of 20 mm must be placed in the intake system, and all engine airflow must pass through it.
The required sequence for a naturally aspirated engine is throttle body, restrictor, and engine.
Therefore, the final intake layout for Bruce places the throttle body upstream of the bought
restrictor, with the plenum and runners downstream of the restrictor feeding the engine.

The restrictor must also be located so that it can be measured during inspection, and the circular
restricting cross-section must not be movable or flexible. This was one reason for using a bought
restrictor rather than manufacturing the restrictor in-house. A bought restrictor reduces the
risk of incorrect throat diameter, poor surface finish, or non-compliant geometry at the main
flow-limiting feature of the system.

From these rules, the main intake design constraints for Bruce are as follows:

• the complete intake system must remain inside the permitted vehicle surface envelope;

• any low-mounted intake components must be protected from impact;

• the intake manifold must be securely attached to the engine using mechanical fasteners;

• significant intake mass or cantilevered sections must be properly supported;

• chassis-mounted supports must allow for engine movement and chassis flex;

• an air filter must be fitted at the entry of the intake system;

• the throttle body must operate smoothly and return reliably without sticking;

• the throttle mechanism must be protected from debris ingress;

• all engine airflow must pass through one circular restrictor;

• for the gasoline-fuelled naturally aspirated engine, the restrictor diameter must not exceed
20 mm;

• the required intake sequence is throttle body, restrictor, and engine;

• the restrictor must be accessible for inspection and measurement;

• the restrictor throat must not be movable or flexible;

• the intake must avoid interference with the chassis, bodywork, fuel system, cooling system,
wiring, exhaust, and driver area.

Overall, the FSUK requirements define the minimum acceptable intake design. The final intake
system must therefore balance theoretical performance aims, such as reduced pressure loss and
improved cylinder filling, with rules compliance, packaging, manufacturability, reliability, sealing,
and serviceability. For Bruce, this led to a compact carbon fibre plenum, a bought 20 mm
restrictor, the original motorcycle throttle body, and short runners suited to the available engine
bay space.

## Design Objectives

The intake system for Bruce was designed to satisfy several engineering objectives at the same
time. While the intake must support good engine breathing and throttle response, it also has to
meet Formula Student packaging requirements, remain practical to manufacture, seal reliably,
and withstand vibration, heat, and repeated assembly. The final design therefore had to balance
performance, compliance, manufacturability, mass, reliability, and serviceability rather than
simply aiming for the largest possible plenum or longest possible runners.

The main design objectives are summarised in Table 1. These objectives guided the selection of
the original Honda CBR600RR throttle body, the bought restrictor, the rounded carbon fibre
plenum, the short runner layout, the gasket design, and the validation plan.

Table 1: Main design objectives for the Bruce intake system

<img width="645" height="772" alt="image" src="https://github.com/user-attachments/assets/9aee0749-6a30-4b8c-9494-a1f956ade219" />

<img width="510" height="772" alt="image" src="https://github.com/user-attachments/assets/80e6368a-2faa-430b-88bd-c0c931fae0df" />

Overall, the objective was not simply to design the highest-flowing intake possible. The final
system had to be a practical Formula Student intake that could be manufactured by the team,
fitted within Bruce, pass inspection, seal reliably, and provide a suitable basis for engine running
and mapping.

## Design Options and Concept Selection

Before finalising the intake system for Bruce, several possible intake concepts were considered.
The aim of this stage was not only to choose the highest-flowing theoretical design, but to select
a concept that could be packaged inside the car, manufactured by the team, sealed reliably, and
validated during engine testing. The intake also had to work around the fixed Formula Student
restrictor requirement, the available Honda CBR600RR throttle body, the engine position, chassis
tubes, fuel system, cooling system, and bodywork.

The main concepts considered were an angular aluminium plenum, a rounded plenum with
runners, a side-entry or cone-style plenum, a dual-plenum arrangement, and a variable geometry
intake. Each concept offered different advantages, but also introduced different risks in terms of
airflow, packaging, manufacturing complexity, sealing, weight, and serviceability.

The previous angular plenum style was attractive because it could be manufactured from sheet
material using relatively simple cutting, folding, and welding methods. However, this type of
design produces sharper internal corners and more abrupt changes in direction. These features
can increase flow separation and make cylinder-to-cylinder distribution less predictable. For this
reason, it was not considered the best direction for the final intake on Bruce.

More complex concepts, such as side-entry plenums, cone-style plenums, dual plenums, and
variable runner systems, offered possible theoretical performance benefits. These designs could
potentially improve pressure recovery, cylinder distribution, or runner tuning. However, they
would also make the system harder to manufacture, package, seal, and inspect. Since the intake
had to be built within the available team timeline and manufacturing capability, these concepts
were not selected for the final design.

The selected direction was a rounded carbon fibre plenum with short runners. This provided the
best overall compromise between airflow, weight, packaging, manufacturability, and reliability.
The rounded shape helps reduce sharp internal corners and flow separation, while the carbon fibre
construction allows a more complex and lightweight shape to be produced using a 3D printed
mould. The short runners keep the intake compact and make the system easier to package around
the engine and chassis.

Table 2: Intake concept comparison

<img width="545" height="235" alt="image" src="https://github.com/user-attachments/assets/7e044cd7-9a23-41f2-a4b1-35c5d916967e" />

<img width="542" height="325" alt="image" src="https://github.com/user-attachments/assets/9ddc705b-c28e-4d58-a377-5b12f7f5e08a" />

### Final Concept Selection

Based on the comparison of the main concepts, the final intake design uses a rounded carbon fibre
plenum, a bought restrictor, the original Honda CBR600RR motorcycle throttle body with only
minor modifications, and short runners feeding the engine. This concept was selected because
it gives the strongest compromise between theoretical intake performance and practical build
feasibility.

The selected design avoids the sharp internal features of a simple angular plenum while also
avoiding the extra complexity of a dual-plenum or variable geometry system. It allows the intake
to remain compact, lightweight, and serviceable, while still providing a smoother plenum shape
and direct runner layout. The use of carbon fibre also allowed the final part to be manufactured
from a 3D printed mould, making the curved plenum shape achievable without expensive tooling.

### Throttle Body Selection

The final design retains the original Honda CBR600RR motorcycle throttle body, with only small
modifications where required for packaging and assembly. This was chosen because the original
throttle body is already designed to operate with the engine and is compatible with the existing
throttle actuation and sensor arrangement. Retaining the original component therefore reduced
design risk compared with manufacturing or adapting a completely custom throttle body.

Using the original throttle body also improves reliability and serviceability. It is a proven OEM
component designed for the operating environment of a high-revving motorcycle engine. The
design work therefore focused on adapting the plenum, restrictor, and intake interfaces around
the original throttle body rather than replacing it unnecessarily.

### Restrictor Selection

The restrictor was bought rather than manufactured in-house. This decision reduced the risk of
dimensional errors, poor surface finish, or an inaccurate throat diameter. Since the restrictor is
the main flow-limiting feature of the intake system, its geometry must be accurate, repeatable,
and suitable for inspection. A bought restrictor provides a more reliable starting point and allows
the team to focus manufacturing effort on the carbon fibre plenum, runner layout, and sealing
interfaces.

The restrictor also has to be sealed properly to the rest of the intake system. Any leak around
the restrictor, throttle body, or plenum would allow unmetered air into the engine and could
make the engine difficult to map consistently. For this reason, the restrictor interface was treated
as a critical joint in the assembly and must be checked during leak testing before engine running.

### Plenum Material Selection

Several material options were considered for the plenum, including aluminium, steel, 3D printed
polymer, and carbon fibre composite. Aluminium would have been relatively easy to fabricate
and modify, but producing a smooth rounded shape would have been more difficult without
more complex forming or welding. Steel would have been strong and easy to weld, but would
add unnecessary mass high on the engine. A 3D printed polymer plenum would have allowed
a complex shape, but would introduce concerns around heat resistance, sealing, stiffness, and
long-term durability.

Carbon fibre was selected because it allowed a lightweight, rounded, and more complex plenum
shape to be manufactured using a 3D printed mould. This made the final design more suitable
than a simple fabricated box while still being achievable with the team’s available tools and
manufacturing capability. The main risks of carbon fibre are local damage around fasteners,
delamination, porosity, and sealing quality, so these issues must be managed through careful
layup, trimming, gasket design, and inspection.

### Runner Arrangement

The final design uses short runners running from the plenum to the engine. The purpose of the
runners is to guide air from the plenum into each cylinder while keeping the flow path as smooth
and direct as possible. Although runner length can be tuned for pressure-wave effects, the final
runner length also had to suit the available space around the engine, chassis, fuel system, and
bodywork.

Short runners were selected because they keep the intake compact and reduce unnecessary
curvature. This makes the final system easier to package and manufacture, while still providing a
clear and direct route from the plenum to the engine ports. The runner entrances should be kept
as smooth and consistent as possible, as large differences in runner geometry can cause uneven
airflow distribution between cylinders. After manufacture, the runners should be inspected to
check for internal steps, blocked areas, sharp resin edges, or poor alignment with the engine
ports.

### Sealing and Interface Selection

The intake contains several important interfaces, including the throttle body connection, restrictor
connection, plenum joint, runner connections, and engine-side sealing faces. These joints are
critical because any air leak downstream of the throttle or restrictor can affect idle stability,
air-fuel ratio, and mapping consistency.

A replaceable gasket was selected for the main plenum sealing face. The gasket was cut from
1.5 mm rubber sheet, providing a practical and serviceable sealing method without relying
only on sealant. This also allows the intake to be removed and reassembled for inspection or
future development. During assembly, the gasket should be compressed evenly using a controlled
tightening pattern, while avoiding excessive fastener load that could damage the carbon fibre.

## Engine Data and Calculation Inputs

Before the intake dimensions could be assessed, the main engine and design inputs for Bruce had
to be defined. The intake system was designed around the 2003 Honda CBR600RR engine, which
is a high-revving, four-cylinder, naturally aspirated motorcycle engine. Since the intake must
supply air to all four cylinders through a single Formula Student restrictor, both the total engine
displacement and the single-cylinder displacement are important for the intake calculations.

The intake calculations were used to guide the runner length, plenum sizing, restrictor flow area,
and general packaging decisions. However, the final design was not based on calculations alone.
Intake behaviour is strongly affected by transient pressure waves, throttle response, restrictor
behaviour, valve timing, cylinder head port geometry, and packaging limits. Therefore, the
calculated values were treated as design guidance, while the final dimensions were also influenced
by the available space around the engine, chassis, bodywork, fuel system, and cooling system.

The main engine data and calculation inputs used for the intake design are shown in Table 3.

Table 3: Engine data and calculation inputs for the 2003 Honda CBR600RR intake.

<img width="507" height="575" alt="image" src="https://github.com/user-attachments/assets/29f5236c-9edc-4085-be5a-b39e70a1dc88" />

<img width="510" height="557" alt="image" src="https://github.com/user-attachments/assets/11b30652-b693-4fe7-8b34-e5e858b4dd23" />

The single-cylinder displacement was calculated from the total engine displacement:

<img width="82" height="47" alt="image" src="https://github.com/user-attachments/assets/9c3ffa72-941e-41a6-8301-285ff527aada" />

where <img width="32" height="22" alt="image" src="https://github.com/user-attachments/assets/799f5196-e901-48e2-9274-362bb4ce12db" /> is the displacement of one cylinder, <img width="22" height="22" alt="image" src="https://github.com/user-attachments/assets/2e693e8b-7bf0-439d-821d-f18e8eab5081" /> is the total engine displacement, and n is the number of cylinders. For the CBR600RR engine:

<img width="171" height="42" alt="image" src="https://github.com/user-attachments/assets/903c1a43-f3b3-49d6-b361-12634b5a41a4" />

The restrictor area was calculated from the restrictor diameter:

<img width="85" height="47" alt="image" src="https://github.com/user-attachments/assets/1d73952e-84cb-4311-9af9-92e7e026528d" />

Using a 20mm restrictor diameter:

<img width="207" height="50" alt="image" src="https://github.com/user-attachments/assets/991cf987-55d6-45e6-b15f-67eda3557101" />

A simplified estimate of the engine volume flow rate can also be made using:

<img width="117" height="52" alt="image" src="https://github.com/user-attachments/assets/008709d3-f5b9-4cfa-b016-88b55a66b108" />

where <img width="32" height="25" alt="image" src="https://github.com/user-attachments/assets/266e2ac2-9c73-457f-8645-931c6580ac83" /> is the intake volume flow rate, <img width="22" height="21" alt="image" src="https://github.com/user-attachments/assets/0b51a6ce-7ebc-44ad-bfb9-f4d2a9e3b25d" /> is the engine displacement, N is the engine speed in revolutions per second, and <img width="21" height="20" alt="image" src="https://github.com/user-attachments/assets/99e40c43-8390-4ca1-afb3-168718dd6362" /> is the volumetric efficiency. The division by two is required because a four-stroke engine only has one intake event every two crankshaft revolutions.

These inputs provide the basis for the intake calculation section. The results should be used
to justify the chosen runner length, plenum volume, restrictor interface, and final packaging
decisions. However, because intake behaviour is highly dependent on pressure waves, restrictor
behaviour, and real engine running conditions, the final design must still be validated using leak
testing, engine running, air-fuel ratio behaviour, and dyno testing where possible.

##Intake Calculation Results

The intake calculations were used to provide a theoretical starting point for the plenum volume,
runner length, restrictor flow area, and general intake layout. These calculations were not treated
as exact final dimensions because intake behaviour is highly dependent on transient pressure
waves, restrictor behaviour, valve timing, cylinder head port geometry, throttle response, and
real engine operating conditions. The final design therefore had to combine calculation results
with CAD packaging, manufacturing capability, available components, and validation testing.

### Single-Cylinder Displacement

The Honda CBR600RR engine has a total displacement of approximately 600 cc and four cylinders.
Since each runner feeds one cylinder, the single-cylinder displacement was calculated as:

<img width="81" height="52" alt="image" src="https://github.com/user-attachments/assets/ec7d6a54-c2e1-4f11-8ef6-d23f9fadc4a9" />

where <img width="31" height="22" alt="image" src="https://github.com/user-attachments/assets/2d5c0835-75f6-4092-9a34-4ebcacb44aa8" /> is the displacement of one cylinder, <img width="21" height="25" alt="image" src="https://github.com/user-attachments/assets/981b8462-28ab-4abb-9916-d37388e081a6" /> is the total engine displacement, and n is the number of cylinders.

<img width="171" height="50" alt="image" src="https://github.com/user-attachments/assets/ee1e6e64-aa34-44b0-8b94-59aeb02e8345" />

Each intake runner therefore supplies one cylinder with an approximate displacement demand of
150 cc per intake event. This value is useful when considering runner sizing, airflow demand, and
the relationship between the plenum and the individual cylinders.

### Restrictor Area

The restrictor is the main flow-limiting feature of the intake system. For a naturally aspirated
gasoline Formula Student engine, the maximum restrictor diameter is 20 mm. The restrictor
area was calculated using:

<img width="86" height="52" alt="image" src="https://github.com/user-attachments/assets/dc40f66d-3b41-4930-ab7a-ac76e6ab148e" />

Where <img width="22" height="27" alt="image" src="https://github.com/user-attachments/assets/96945537-732d-45e4-8753-fe21ed8a704e" /> is the restrictor cross-sectional area and d is the restrictor diameter.

<img width="210" height="55" alt="image" src="https://github.com/user-attachments/assets/a3d225bf-5375-4852-aaeb-dfa2e778d1f0" />

This small area shows why the restrictor dominates the intake design. Since all engine airflow
must pass through this throat, the rest of the intake should avoid adding unnecessary pressure
losses. Sharp corners, poor surface finish, sudden expansions, leaks, or badly aligned joints
downstream of the restrictor would reduce the pressure available to the engine and make mapping
more difficult.

### Theoretical Airflow Demand

A simplified estimate of the intake volume flow rate can be made using:

<img width="117" height="52" alt="image" src="https://github.com/user-attachments/assets/fe27cfb3-1736-470b-8fae-5e4db635fe42" />

where <img width="30" height="27" alt="image" src="https://github.com/user-attachments/assets/ad449da9-25f1-4bc1-86ae-bdf785fbff2f" /> is the theoretical intake volume flow rate, <img width="22" height="22" alt="image" src="https://github.com/user-attachments/assets/53a2c6fb-24fb-4cbf-9cf0-408eee55b4d6" /> is the total engine displacement, N is the engine speed in revolutions per second, and <img width="21" height="20" alt="image" src="https://github.com/user-attachments/assets/92e3bbfa-4840-4749-af9e-b8bca4bf99ea" /> is the volumetric efficiency. The division by two
is required because a four-stroke engine only completes one intake event every two crankshaft
revolutions.

Assuming <img width="17" height="20" alt="image" src="https://github.com/user-attachments/assets/a6602529-9fa1-465b-9190-e329ecefeb66" /> = 1.0 for a simple comparison, the theoretical intake flow demand at 6000 rpm is:

<img width="342" height="182" alt="image" src="https://github.com/user-attachments/assets/23c5b998-e90e-40e0-8f75-319670b2eb26" />

At 11000 rpm, the same simplified estimate gives:

<img width="352" height="182" alt="image" src="https://github.com/user-attachments/assets/1dfc26b5-17d5-4250-8d9e-d5855cb1a4c7" />

These values are only theoretical estimates, but they show the scale of the airflow demand through
the restrictor and plenum. In reality, the actual flow will be affected by restrictor losses, throttle
position, air temperature, pressure-wave behaviour, volumetric efficiency, and engine mapping.

### Approximate Restrictor Velocity

Using the theoretical volume flow rate and the restrictor area, the average velocity through the
restrictor can be estimated from:

<img width="81" height="60" alt="image" src="https://github.com/user-attachments/assets/0cafd102-b74a-4e84-8c21-c90696d1b8a1" />

At 6,000 rpm:

<img width="235" height="52" alt="image" src="https://github.com/user-attachments/assets/f71f10b9-4b3c-4a17-8430-8fb0f44543e3" />

At 11,000 rpm:

<img width="230" height="52" alt="image" src="https://github.com/user-attachments/assets/12c2bb45-7ad1-4e47-bf23-c3938174ef7c" />

These values are approximate and do not include compressibility effects, discharge coefficient,
or choking behaviour. However, they demonstrate why pressure recovery after the restrictor is
important. The high velocity through the restrictor means that any additional losses caused
by poor plenum geometry, sharp transitions, or leakage would have a noticeable effect on the
pressure available at the runners.

### Runner Length Result

The runner length calculation was used to estimate a sensible starting point for the intake runner
geometry. The ideal runner length depends on the target engine speed, intake valve timing, wave
speed, cylinder head port length, and the harmonic order assumed in the pressure-wave model.
For this reason, the result should be treated as a guide rather than an exact fixed value.

The earlier intake calculation work indicated that a runner length of approximately 100–125 mm
was a suitable starting point for the Honda CBR600RR package once the intake path inside the
cylinder head was considered. This range gives a compact runner length that is more practical
for the available space around the engine and chassis.

The final intake design therefore uses short runners. This decision was not based only on the
calculation result, but also on packaging and manufacturability. Longer tuned runners may offer
theoretical pressure-wave benefits at certain engine speeds, but they would be harder to package,
may require more curvature, and could increase the size and mass of the intake assembly. The
short runner layout provides a more practical compromise for Bruce.

### Plenum Volume Result

The plenum volume was not defined by a single exact equation because the plenum acts as part of
an unsteady intake system. Its behaviour depends on the restrictor, throttle body, runner layout,
engine speed, cylinder demand, and pressure-wave reflections. A larger plenum can improve
pressure stability, but may reduce throttle response because a larger volume of air must be filled
or emptied during throttle changes. A smaller plenum may improve response, but can increase
pressure fluctuations and make cylinder-to-cylinder distribution less stable.

For this reason, the plenum calculation was used as a design check rather than a fixed requirement.
The final plenum volume should be taken from the SolidWorks CAD model and compared with
the total engine displacement. Since the engine displacement is approximately 0.6 L, the final
CAD plenum volume should be recorded and assessed against the packaging space available on
Bruce.

<img width="270" height="50" alt="image" src="https://github.com/user-attachments/assets/6f264df5-3c1d-4b5d-9c97-665d8c7672d4" />

where <img width="57" height="27" alt="image" src="https://github.com/user-attachments/assets/46cf54cc-b26f-497a-a16b-271bb623e6b5" /> is the measured CAD plenum volume and <img width="22" height="22" alt="image" src="https://github.com/user-attachments/assets/ffbbb4db-1db2-4cd8-b567-9772eb16f7b8" /> is the total engine displacement.

<img width="270" height="55" alt="image" src="https://github.com/user-attachments/assets/3b5a6273-12da-462a-8230-63e0b5707e6d" />

This ratio should be added once the final CAD volume is measured. It gives future team members
a simple way to compare this intake against future designs, even if the exact plenum shape
changes.

### Summary of Calculated and Selected Intake Dimensions

Table 4: Summary of calculated and selected intake dimensions

<img width="535" height="737" alt="image" src="https://github.com/user-attachments/assets/b2d1bec4-2186-49a6-a6ee-ee1b49fd531e" />

### Calculation Interpretation

The calculation results show that the restrictor is the dominant flow limitation in the intake
system (Shocker I know) , while the runner length and plenum volume must be treated as compromise values. The
20 mm restrictor gives a cross-sectional area of only 314 mm2, so the intake design must avoid
unnecessary additional pressure losses. This supports the use of a smoother rounded plenum,
careful restrictor sealing, and short direct runners.

The runner length calculation suggested that a compact runner length of approximately 100–125
mmwas a sensible starting point once the cylinder head intake path was included. This supports
the final decision to use short runners rather than a long, complex, or variable geometry runner
system. The final runner geometry should still be checked for smooth entries, good alignment,
and consistent cylinder-to-cylinder flow paths.

The plenum volume calculation was less definitive because the plenum operates under unsteady
conditions. The final plenum volume should therefore be validated using engine running data,
air-fuel ratio behaviour, throttle response, and dyno testing where possible. If more time is
available, pressure sensors, WAVE modelling, or CFD could be used to compare the manufactured
intake with the earlier concept work and guide future design improvements.

## CAD Development and Design Iterations

The CAD development of the intake system was mainly driven by packaging. Unlike the exhaust,
where the pipe route could be adjusted over a longer path, the intake had to fit in a relatively
small region above the engine while still remaining inside the permitted vehicle envelope. The air
filter, throttle body, restrictor, plenum, and runners all had to be positioned around the chassis
tubes, engine, fuel system, cooling system, bodywork, and available service access.

One of the main difficulties during the CAD stage was using the vehicle envelope as a design
constraint. A reference plane was created from the allowable envelope and used as a guide to
check whether the plenum and restrictor location remained inside the permitted space. This was
useful because it gave a clear visual limit while modelling. However, it also made the design
process more iterative, as small changes to the plenum shape, restrictor angle, or throttle body
position could cause the intake to move outside the available space or interfere with surrounding
components.

The restrictor location was another major issue during the early CAD development. For a
significant part of the design process, the restrictor position was adjusted by eye to try to find a
workable compromise between airflow direction, throttle body alignment, plenum shape, and
packaging. This made the process slower than expected because each change affected several
other parts of the intake. Moving the restrictor improved one area of the design, but could then
create a new issue with the plenum volume, runner entry angle, bodywork clearance, or throttle
body connection.

This approach showed that the restrictor should have been treated as one of the primary fixed
references earlier in the CAD process. Since the restrictor defines the main airflow path into the
plenum and must also satisfy Formula Student inspection requirements, its position has a large
effect on the rest of the intake. Once the restrictor location was better constrained, the plenum
shape and runner layout could be developed more consistently around it.

Several design iterations were therefore required before the final intake layout was selected.
Earlier versions focused mainly on fitting the plenum under the envelope plane and connecting
the restrictor to the throttle body. Later versions placed more emphasis on smoothing the
plenum shape, improving the runner entries, reducing unnecessary curvature, and ensuring that
the intake could be manufactured using a 3D printed mould and carbon fibre layup process.
The final design is not simply the theoretically ideal intake shape, but a practical compromise
between the available packaging space, restrictor position, throttle body location, runner layout,
manufacturability, and serviceability.

A key lesson from the CAD development process is that future intake designs should define
the main hard points earlier. These include the engine port locations, throttle body position,
restrictor position, permitted envelope boundary, air filter space, and required service clearances.
Fixing these reference points at the start would reduce the amount of trial-and-error modelling
and make it easier to compare design iterations objectively. Despite the difficulty, the final CAD
process allowed the intake to develop from a rough packaging concept into a compact carbon
fibre plenum design that could be manufactured and fitted to Bruce.

## Final Intake Design for Bruce

The final intake design for Bruce uses a rounded carbon fibre plenum, a bought restrictor,
the original Honda CBR600RR motorcycle throttle body with only minor modifications, and
short runners feeding the engine. This layout was selected because it provides the best overall
compromise between airflow performance, packaging, manufacturability, reliability, mass, and
serviceability.

The intake air path begins at the air filter before passing through the original motorcycle throttle
body. From there, the air passes through the bought restrictor, which is the main flow-limiting
feature of the system. Downstream of the restrictor, the air expands into the carbon fibre plenum
before being distributed through the short runners into the engine cylinders. This arrangement
follows the required intake sequence while keeping the system compact and suitable for the
available space around the engine.

The rounded plenum shape was chosen to reduce the sharp internal corners and abrupt changes in
direction that would occur in a simpler angular box-style plenum. A smoother shape is preferred
because it helps reduce flow separation and unnecessary pressure losses after the restrictor. Since
the restrictor already limits the maximum airflow available to the engine, the downstream plenum
and runner layout should avoid adding further avoidable losses.

Carbon fibre was selected for the plenum because it allowed a lightweight and more complex
rounded shape to be manufactured using a 3D printed mould. Compared with a welded aluminium
or steel plenum, the carbon fibre design reduces mass and gives more freedom in shaping the
plenum around the packaging constraints of the car. This was particularly useful because the
intake had to fit within the allowable vehicle envelope while avoiding the chassis, bodywork, fuel
system, cooling system, wiring, and other powertrain components.

The original Honda CBR600RR throttle body was retained to reduce design risk. It is already
designed to work with the engine and is compatible with the existing throttle actuation and
sensor arrangement. This avoided the additional complexity of designing a new throttle body
or adapting a different unit. Only small modifications were required to suit the final intake
packaging and assembly.

The restrictor was bought rather than manufactured in-house. This reduced the risk of producing
an inaccurate throat diameter, poor surface finish, or non-compliant restrictor geometry. Since the
restrictor is the most important flow-limiting part of the intake system, maintaining dimensional
accuracy at this point was considered more important than manufacturing it internally. The
bought restrictor also provided a reliable reference component around which the plenum and
throttle body connection could be designed.

The final runner arrangement uses short runners from the plenum to the engine. Short runners
were selected mainly because of packaging limitations and the need to keep the intake compact.
Although runner length can be tuned for pressure-wave effects, the available space around the
engine and chassis limited the practical runner length. The final layout therefore prioritises a
compact, direct, and manufacturable runner arrangement rather than a more complex long-runner
or variable-geometry design.

Sealing was treated as a critical part of the final design. A 1.5 mm rubber sheet was used to cut
the main plenum gasket, providing a simple and replaceable sealing method. This allows the
intake to be assembled and removed without relying only on sealant. The gasket also improves
serviceability because it can be replaced if it becomes damaged during inspection, testing, or
future development.

Overall, the final intake design is a practical Formula Student solution rather than a purely
theoretical optimum. It uses the available Honda throttle body, a bought restrictor, a lightweight
carbon fibre plenum, short runners, and a replaceable gasket to produce a compact and serviceable
intake system for Bruce. The final design should now be validated through leak testing, throttle
operation checks, engine running, AFR behaviour, heat inspection, and dyno testing where
possible.

## Material Selection

The main material selected for the intake plenum was carbon fibre composite. This was chosen
because it provides a strong and lightweight structure while allowing a more complex rounded
shape to be manufactured compared with a simple welded metal box. For an intake plenum,
this is useful because smoother geometry helps reduce sharp internal corners, flow separation,
and unnecessary pressure losses after the restrictor. The use of carbon fibre also allowed the
final plenum shape to be produced using a 3D printed mould, which made the design achievable
without expensive CNC tooling or complex sheet metal forming.

Carbon fibre was also attractive because of its low mass. The intake is mounted high on the
engine, so reducing mass in this area helps reduce the load on the intake mounts, throttle body
interface, and cylinder head. A lighter plenum also reduces vibration loading during engine
operation. Compared with a steel or aluminium plenum of similar size, a carbon fibre plenum
provides a better strength-to-weight ratio and gives more freedom to shape the part around the
packaging constraints of Bruce.

Another benefit of carbon fibre composite is its lower thermal conductivity compared with
aluminium. This can help reduce heat transfer from the engine bay into the intake air. Cooler
intake air is denser, which can improve the mass of air entering the engine. However, the material
choice alone does not define intake performance. The main performance factors are still the
restrictor, plenum geometry, runner layout, sealing quality, and engine calibration. Therefore,
carbon fibre was selected mainly because it provided a lightweight and manufacturable way of
producing the required rounded plenum shape.

The main disadvantages of carbon fibre are manufacturing sensitivity, sealing risk, and local
damage around holes or fasteners. Unlike a metal plenum, a composite part can suffer from
porosity, delamination, cracking, resin-rich areas, dry fibres, or damage caused by over-tightened
fasteners. Carbon fibre is also less tolerant of point loading than metal, especially around drilled
holes and flange joints. For this reason, the final design must avoid using the plenum as a
structural support and should use washers, backing plates, inserts, or local reinforcement where
fastener loads are applied.

The manufacturing process also affects the final material quality. During layup, care must be
taken to avoid wrinkles, bridging, trapped air, dry areas, and poor resin distribution. These
defects could reduce strength, cause leaks, or create weak points in the plenum. After curing,
the part should be inspected visually for cracks, delamination, exposed fibres, resin voids, and
surface defects. Any drilled or trimmed edges should be checked carefully because exposed fibres
or rough edges can become initiation points for damage.

A 1.5 mm rubber sheet was used to cut the main plenum gasket. This provided a simple,
low-cost, and practical method of sealing the plenum joint. The gasket could be cut to match
the required flange shape and bolt pattern, allowing the intake to be assembled without relying
only on sealant. This improves serviceability because the gasket can be removed and replaced if
it becomes damaged during testing, inspection, or future development.

The gasket also helps protect the carbon fibre sealing face by spreading the clamping load more
evenly across the joint. However, the gasket only works correctly if the sealing faces are reasonably
flat and the fasteners are tightened evenly. During assembly, the bolts should be tightened
gradually in a cross-pattern to avoid distorting the flange or crushing the composite locally.
Excessive tightening should be avoided, as this could damage the carbon fibre or permanently
deform the gasket.

Overall, carbon fibre was selected because it allowed a lightweight, rounded, and manufacturable
plenum to be produced for Bruce. The material is well suited to the final intake concept, but
it requires careful manufacturing, sealing, fastening, and inspection. The use of a replaceable
rubber gasket, controlled tightening procedure, and post-manufacture inspection helps reduce
the main risks associated with using a composite intake plenum.

## Component Availability and Supplier Constraints

To be complete.

## Manufacturing Preparation: Mould, Templates and Interfaces

Before manufacturing the final carbon fibre intake plenum, the main preparation work focused
on the mould design, interface locations, sealing faces, runner openings, restrictor connection,
and gasket templates. This stage was important because any errors in the mould or interface
positions would be transferred directly into the final composite part. Unlike a metal plenum,
which can be cut and re-welded more easily, a carbon fibre plenum is much harder to modify
after curing without affecting strength, sealing, or surface quality.

The mould was developed from the final CAD geometry of the plenum. Since the selected intake
design used a rounded shape rather than a simple angular box, a 3D printed mould was chosen
as the most practical manufacturing method. This allowed the curved plenum surface to be
produced without requiring CNC-machined tooling, metal forming, or complex welded fabrication.
The mould also allowed the design to keep the smoother geometry that was selected during the
concept stage.

The mould preparation had to consider both the outside shape of the plenum and how the cured
carbon fibre part would be removed after layup. Any sharp corners, undercuts, or poorly chosen
split lines could make release difficult and could damage the part during demoulding. For this
reason, the mould design had to be checked before printing to ensure that the part could be
released without excessive force. The mould surface also needed to be prepared before layup so
that the carbon fibre would not bond permanently to the printed mould.

The main interfaces were also defined before manufacture. These included the throttle body
interface, restrictor interface, runner openings, plenum joint, gasket face, and fastener positions.
These areas were treated as critical features because they control the alignment, sealing, and
serviceability of the intake system. Poor alignment at any of these interfaces could cause air
leaks, internal steps, flow disruption, or difficulty assembling the intake on the engine.

The restrictor and throttle body interfaces were especially important because they define the
main airflow path into the plenum. The bought restrictor was used as a reference component to
reduce the risk of manufacturing an inaccurate throat diameter or poor sealing surface. Before
cutting or drilling the carbon fibre part, the restrictor and throttle body positions had to be
checked against the CAD model and the physical components. This reduced the risk of cutting
openings in the wrong position or creating a joint that could not be sealed properly.

The runner interface preparation was also important. The runners had to line up with the engine
ports while remaining compatible with the plenum shape and available packaging space. Any
mismatch between the runners and plenum could create an internal step or sharp edge, which
would disturb the flow entering the cylinders. The runner openings therefore had to be marked
carefully and inspected after cutting to ensure that there were no blocked areas, rough resin
edges, or large geometry differences between cylinders.

Templates were used where possible to improve repeatability during cutting and assembly. The
gasket template was particularly important because the final plenum used a 1.5 mm rubber sheet
as the main sealing gasket. The gasket had to match the flange shape, bolt-hole pattern, and
intake openings so that it could seal correctly without blocking the airflow path. Preparing the
gasket template before final assembly reduced the chance of misalignment and made it easier to
replace the gasket in the future if it became damaged.

Fastener locations were also planned before drilling the final part. Since carbon fibre can be
damaged by point loading, the bolt positions had to provide enough clamping force for sealing
without crushing or cracking the composite. Where possible, washers, backing plates, inserts, or
local reinforcement should be used to spread the load around holes. The tightening pattern also
had to be considered so that the gasket would be compressed evenly during assembly.

The preparation stage therefore acted as a bridge between the CAD model and the physical
manufacturing process. It ensured that the mould, interface positions, gasket shape, runner
openings, restrictor connection, and fastener layout were all considered before the carbon fibre
part was finished. This reduced the risk of manufacturing errors and helped make the final intake
easier to assemble, seal, inspect, and maintain on Bruce.

## Manufacturing Process

The intake plenum was manufactured using a mould-based carbon fibre process. This method
was selected because the final design used a rounded plenum shape, which would have been
difficult to manufacture accurately from flat metal sheet. A 3D printed mould allowed the CAD
geometry to be transferred into a physical tool without requiring CNC machining or complex
metal forming.

The first stage of manufacture was producing the mould from the final CAD model. The mould
was designed around the required plenum shape and then manufactured using 3D printing. Before
layup, the mould surface was prepared to improve the surface finish of the carbon fibre part
and to allow the cured plenum to be released without damage. This preparation stage was
important because any rough areas, print lines, or mould defects could be transferred into the
final composite surface.

Once the mould was prepared, the carbon fibre material was cut and arranged to suit the plenum
geometry. The layup had to follow the curved mould surface while avoiding wrinkles, bridging,
dry areas, and trapped air. Particular care was required around the flange, runner openings,
restrictor connection, and any tight-radius areas because these regions are more likely to suffer
from poor fibre contact or resin build-up. Additional local reinforcement should be added where
fasteners, sealing faces, or interface loads are expected.

Resin was then applied to the carbon fibre and the part was left to cure. During curing, the
main aim was to maintain good contact between the carbon fibre and the mould so that the
final plenum shape matched the CAD design as closely as possible. After curing, the plenum
was carefully released from the mould and inspected for obvious manufacturing defects such as
cracks, delamination, porosity, exposed fibres, resin-rich areas, or dry patches.

After the carbon fibre shell was produced, the part was trimmed to its final outline. The required
openings were then finished for the restrictor, throttle body connection, runner connections, and
plenum sealing face. These operations had to be carried out carefully because carbon fibre can
delaminate or crack if cut aggressively. Any drilled or trimmed edges should be cleaned and
inspected to ensure that there are no loose fibres, sharp resin edges, or damaged areas that could
affect sealing or airflow.

The runner openings were checked to ensure that they were not blocked and that there were no
major internal steps or rough edges. This was important because poor runner alignment or sharp
internal features could disturb the airflow entering the cylinders. The restrictor and throttle
body openings were also checked against the physical components to confirm that the parts could
be assembled without forcing or misalignment.

The main plenum gasket was cut from 1.5 mm rubber sheet. The gasket was made to match
the flange shape, bolt-hole pattern, and intake openings. This provided a replaceable sealing
method and avoided relying only on sealant during assembly. The gasket holes were aligned with
the plenum holes so that the joint could be clamped evenly and so that the gasket would not
obstruct the internal airflow path.

During final assembly, the throttle body, restrictor, runners, gasket, and plenum were brought
together and checked for alignment. The fasteners should be tightened gradually using a controlled
cross-pattern so that the gasket is compressed evenly across the sealing face. Over-tightening
must be avoided because excessive local load can crush the gasket, distort the sealing surface, or
damage the carbon fibre around bolt holes. Where possible, washers, backing plates, inserts, or
local reinforcement should be used to spread fastener loads into the composite.

After assembly, the intake should be inspected before engine running. The inspection should
check that the throttle operates freely, the restrictor and plenum joints are seated correctly, the
runners are aligned, the gasket is not pinched or displaced, and the intake is properly supported.
Any signs of cracking, delamination, loose fasteners, or poor sealing should be corrected before
the intake is fitted to Bruce for leak testing and engine validation.

Overall, the manufacturing process allowed a lightweight and rounded carbon fibre plenum to be
produced from the final CAD design using a realistic team manufacturing method. The main
manufacturing risks were composite quality, trimming accuracy, sealing surface flatness, and local
fastener loading. These risks were managed through mould preparation, careful layup, post-cure
inspection, controlled trimming, gasket use, and careful assembly.

## Assembly and Interfaces

The intake assembly contains several important interfaces, including the throttle body connection,
restrictor connection, plenum joint, runner connections, engine-side sealing faces, gasket, and
any support brackets. These interfaces are critical because they affect sealing, airflow alignment,
throttle operation, structural support, and serviceability. Any poor fit, misalignment, or damaged
sealing surface could lead to air leaks, unstable idle, poor mapping consistency, or local damage
to the carbon fibre plenum.

Before assembly, the carbon fibre plenum should be inspected carefully. The inspection should
check for cracks, delamination, resin-rich areas, dry fibres, exposed fibres, rough trimmed edges,
and blocked internal sections. The runner openings should also be checked to make sure that
there are no sharp resin edges, loose fibres, or internal steps that could disturb the airflow into
the engine. The throttle body, restrictor, runners, gasket, fasteners, washers, and any brackets
should also be checked for cleanliness, damage, and correct fitment.

The main plenum gasket is cut from 1.5 mm rubber sheet and should be placed between the
sealing faces before the plenum is tightened. The gasket must be aligned with the bolt holes and
intake openings so that it seals the joint without obstructing the airflow path. If the gasket is
pinched, displaced, torn, or overhanging into the intake path, it should be corrected or replaced
before final assembly.

The plenum fasteners should be tightened gradually using a controlled cross-pattern. This helps
compress the gasket evenly and reduces the risk of distorting the sealing face. Over-tightening
must be avoided because excessive local load can crush the gasket, crack the carbon fibre, or
cause delamination around bolt holes. Where possible, washers, backing plates, inserts, or local
reinforcement should be used to spread the fastener loads into the composite structure.

The throttle body and restrictor interface should be checked to make sure that the joint is fully
seated and that the airflow path is not stepped or misaligned. The throttle plate should be
opened and closed through its full range of motion after assembly to confirm that it moves freely,
returns reliably, and does not foul the plenum, restrictor, cable routing, or nearby components.
Any stiffness, sticking, or interference must be corrected before the engine is run.

The runner interfaces should be checked for alignment with the engine ports. Poor runner
alignment can cause sealing issues and can also disturb the flow entering each cylinder. The
runners should sit correctly without forcing the plenum into position. If the intake has to be
pulled into alignment using the fasteners, this may introduce stress into the carbon fibre or cause
the gasket to seal unevenly.

Once the intake has been assembled, it should be mounted to the engine and any support brackets
should be fitted. The intake must not be left unsupported if its mass creates a large bending
load on the cylinder head, throttle body, restrictor, or plenum joints. The support arrangement
should hold the intake securely while still allowing for engine vibration and movement. If a
chassis-mounted support is used, it should include suitable compliance or isolation so that chassis
flex does not transfer excessive load into the carbon fibre plenum.

After the intake is fitted to Bruce, the full assembly should be checked against the chassis,
bodywork, fuel system, cooling system, wiring, exhaust, and driver envelope. The air filter,
throttle body, restrictor, plenum, runners, and support brackets should all have sufficient clearance
from hot, sharp, or moving parts. The final assembly should then be leak-tested and inspected
again after the first engine run to check for gasket compression, loose fasteners, movement,
cracking, or signs of air leakage.

Overall, the assembly process must ensure that the intake is sealed, aligned, supported, and
serviceable. The carbon fibre plenum provides a lightweight and compact solution, but it must
be assembled carefully to avoid local damage, uneven gasket compression, or vibration-related
failure during engine running.

## Validation and Testing Plan

After the intake has been manufactured and assembled, it must be validated before the car is run
under load. The purpose of the validation plan is to confirm that the intake fits correctly, seals
properly, allows reliable throttle operation, and does not suffer from vibration, heat, or composite
damage during engine running. Since the intake is made from carbon fibre and includes several
sealed interfaces, testing must focus on both performance and reliability.

The validation process should begin with static checks before progressing to idle testing, controlled
throttle testing, and dyno or track validation. Any failure during the early stages should be
corrected before moving to higher-load engine testing. The main validation stages are summarised
in Table 5.

Table 5: Intake validation and Testing plan

<img width="532" height="616" alt="image" src="https://github.com/user-attachments/assets/b5108c85-5f23-4eae-ba10-72f553664378" />

<img width="535" height="402" alt="image" src="https://github.com/user-attachments/assets/c20ddf4c-b161-471c-9889-2f19f03d415b" />

The intake should only be considered ready for extended running once the static fitment, throttle
operation, leak test, idle test, and post-run inspection have been passed. Dyno or controlled
running should then be used to confirm that the intake behaves consistently under load and does
not introduce mapping instability, air leaks, or heat-related issues.

## Risks, Issues, and Future Improvements

Although the final intake design provides a practical and lightweight solution for Bruce, several
risks remain because the system uses a carbon fibre plenum, multiple sealed interfaces, and a
restrictor-controlled airflow path. The main risks are related to sealing, composite durability,
heat exposure, vibration, runner alignment, and limited validation data. These risks should be
managed through careful assembly, inspection, leak testing, and future engine testing.

Table 6: Intake risks, issues, and future improvements

<img width="507" height="667" alt="image" src="https://github.com/user-attachments/assets/68e2210b-8fe7-489f-ac00-79da643d6214" />

<img width="507" height="787" alt="image" src="https://github.com/user-attachments/assets/928e2fb6-ffee-46ee-9867-c14dce6a1948" />

The most important immediate risks are air leakage, throttle operation, composite damage, and
heat exposure. These should be checked before any extended running. For future iterations,
the main improvement would be to define the restrictor position, runner geometry, and plenum
volume earlier in CAD, then validate the final design using dyno data, AFR behaviour, pressure
measurements, and comparison with WAVE or CFD models

## Previous Intake Concept Work

The intake concept overview is included to show the design direction that informed the final
rounded carbon fibre plenum concept. The full concept overview is only one page, so the complete
PDF is included.

<img width="862" height="637" alt="image" src="https://github.com/user-attachments/assets/a573606e-a108-4337-88a6-3a46cc91b5c9" />

## Intake Interface Research

The most relevant interface pages are included here. These cover the interface requirements,
restrictor-to-plenum concepts, plenum-to-runner concepts, and the final recommendation. The
full interface document does not need to be included in the main body because the important
design reasoning is already summarised in the report.

<img width="867" height="572" alt="image" src="https://github.com/user-attachments/assets/de72624e-29f3-4d27-b0ef-d98b297437a4" />

<img width="912" height="612" alt="image" src="https://github.com/user-attachments/assets/7f15a8ed-967c-4529-8091-3c1c2ce0f198" />

<img width="911" height="687" alt="image" src="https://github.com/user-attachments/assets/2baba8dc-2f10-4d1e-8724-6cf8cffbf974" />

<img width="906" height="495" alt="image" src="https://github.com/user-attachments/assets/bfef70fe-4d31-419e-9883-5c40e8340db2" />

## Intake Calculations

The most relevant calculation pages are included here. These show the restrictor/flow equations, plenum volume reasoning, and runner length estimates.

<img width="605" height="662" alt="image" src="https://github.com/user-attachments/assets/83c9ed9b-9a9b-4327-832d-f149471b872c" />

<img width="692" height="242" alt="image" src="https://github.com/user-attachments/assets/2312786a-2c92-4081-973b-9888281ff13e" />

<img width="690" height="472" alt="image" src="https://github.com/user-attachments/assets/9c52a3c7-5612-4457-8abc-840ef232a82a" />

<img width="700" height="392" alt="image" src="https://github.com/user-attachments/assets/4a13a012-0e51-4d9a-b0e2-ce3aed53629d" />

<img width="692" height="432" alt="image" src="https://github.com/user-attachments/assets/5de472d4-ec83-4f0f-947a-0954c7a253a5" />

<img width="682" height="392" alt="image" src="https://github.com/user-attachments/assets/a643bc2a-a60d-4afa-974d-053b65413c2f" />

<img width="757" height="567" alt="image" src="https://github.com/user-attachments/assets/012ef420-9db1-4377-a4ff-c197cee3ae14" />

## Composite Intake Research

The composite intake research is included to justify the use of a carbon fibre plenum and to
record the manufacturing risks associated with sealing, delamination, heat, and fastener loading.

<img width="591" height="727" alt="image" src="https://github.com/user-attachments/assets/c27be787-1e4f-420b-a682-c356675fbe8f" />

<img width="711" height="767" alt="image" src="https://github.com/user-attachments/assets/5b730305-24bf-4cb9-b6df-02b3b44fe48b" />

<img width="702" height="82" alt="image" src="https://github.com/user-attachments/assets/ae924f88-9300-4196-92fa-3c5f96920504" />

<img width="692" height="772" alt="image" src="https://github.com/user-attachments/assets/e08365f9-bfdf-4622-a97b-6c9ddd8b418e" />

<img width="682" height="70" alt="image" src="https://github.com/user-attachments/assets/8cfcc6e1-56ac-4ed2-b040-e56044b1c972" />

<img width="685" height="442" alt="image" src="https://github.com/user-attachments/assets/7840b312-8cb6-48e2-b472-39257d2eab0d" />














































































