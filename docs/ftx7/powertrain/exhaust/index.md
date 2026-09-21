# Exhaust

## What is an exhaust and why do we need it?

The exhaust system is a critical component of an internal combustion engine, responsible for collecting and directing combustion products away from the engine while influencing overall engine performance. During the combustion process, high-temperature and high-pressure gases are generated within the cylinder. These gases must be efficiently evacuated to allow the cylinder to be refilled with a fresh air-fuel mixture during the subsequent intake cycle.[1]

In a Formula Student vehicle, the exhaust system serves several important functions. Firstly, it provides a controlled path for the safe removal of hot exhaust gases away from the engine and driver. Secondly, it reduces engine noise to comply with Formula Student sound regulations. Most importantly from a performance perspective, the exhaust system can be tuned to improve cylinder scavenging and volumetric efficiency through the manipulation of pressure waves generated during the exhaust process.

<img width="807" height="237" alt="image" src="https://github.com/user-attachments/assets/d2cf64df-a56b-4a9c-af53-8c07588ef315" />

Figure 1: Primary runners, merge collectors, and muffler layout of the exhaust system.

A typical Formula Student exhaust system consists of four primary components: the exhaust ports, primary runners (headers), collector, and muffler. The exhaust ports provide the initial exit path for combustion gases from the cylinder head. The primary runners transport these gases away from the engine while generating pressure waves that can be utilised for performance enhancement. The collector merges the flow from multiple cylinders into a common outlet, while the muffler attenuates noise before the gases are discharged to the atmosphere through the tailpipe.

The design of the exhaust system has a significant influence on engine torque characteristics, power output, throttle response, packaging constraints, weight, and compliance with competition regulations. Consequently, careful consideration must be given to runner geometry, collector design, system length, and acoustic performance during the design process.

## Science behind an Exhaust

The exhaust system operates as a combination of fluid dynamics, thermodynamics, and acoustics. Although it may appear to be a simple network of pipes, its design has a significant influence on engine breathing, torque delivery, noise output, and overall engine performance. In a Formula Student application, the exhaust must therefore be treated as an engineered flow system rather than simply a route for discharging gases.[3]

<img width="1140" height="662" alt="image" src="https://github.com/user-attachments/assets/c8af3df8-63cd-4984-91e6-91f471a3bde6" />

Figure 2: Four Stroke Engine Cycle

During the exhaust stroke, the piston forces high-temperature combustion products out of the cylinder through the exhaust valve. These gases leave the cylinder as a series of high-pressure pulses rather than as a steady continuous flow. Each time an exhaust valve opens, a pressure pulse travels down the primary runner, followed by the movement of the exhaust gas itself. This means that two processes occur simultaneously: the physical movement of gas particles through the pipe, and the propagation of pressure waves through the exhaust system.[3]

One of the main objectives of exhaust design is to minimise flow restriction. If the exhaust system contains sharp bends, poor collector geometry, sudden area changes, or an undersized pipe diameter, the engine must perform additional pumping work to force the gases out of the cylinder. This restriction is commonly referred to as backpressure. Excessive backpressure reduces the effectiveness of the exhaust stroke, increases residual gas trapped in the cylinder, and can reduce the amount of fresh air-fuel mixture entering during the next intake event. As a result, the engine may suffer from reduced volumetric efficiency, lower power output, and poorer throttle response.[4]

However, exhaust design is not simply a case of using the largest possible pipe diameter. If the pipe diameter is too large, exhaust gas velocity can decrease, weakening the energy of the exhaust pulse and reducing the effectiveness of scavenging. A well-designed exhaust therefore aims to balance low restriction with sufficient gas velocity. This is particularly important in naturally aspirated engines, where the exhaust system can be used to assist cylinder emptying and improve engine breathing without forced induction.

Scavenging is one of the most important performance mechanisms in an exhaust system. When an exhaust pulse travels through the primary runner and reaches an area change, such as a collector, part of the pressure wave is reflected back toward the cylinder. Depending on the geometry of the system, this reflected wave can return as a negative-pressure wave. If this negative-pressure wave arrives at the exhaust valve during valve overlap, it can help draw remaining burnt gases out of the cylinder. This reduces residual gas fraction and can also assist the initial movement of the fresh intake charge into the cylinder.[2]

<img width="590" height="416" alt="image" src="https://github.com/user-attachments/assets/48b2541c-4e3c-467a-a609-ba726c84636c" />

Figure 3: Exhaust Port Pressure

The timing of this reflected wave is strongly dependent on runner length, exhaust gas temperature, engine speed, and collector geometry. Longer runners generally tune the scavenging effect for lower engine speeds, while shorter runners tend to favour higher engine speeds. This is because the reflected wave must travel down the runner and return to the exhaust valve at a specific point in the engine cycle. If the wave arrives too early or too late, the scavenging benefit is reduced and, in some cases, the reflected wave can negatively affect cylinder filling.

The collector also plays a major role in exhaust tuning. In a multi-cylinder engine, each primary runner carries pulses from an individual cylinder. The collector merges these pulses into a common outlet and influences how the pressure waves interact. A poorly designed collector can cause pulses from different cylinders to interfere with each other, increasing restriction and reducing scavenging efficiency. A well-designed collector promotes smoother flow merging, maintains gas velocity, and improves the strength and timing of useful pressure-wave reflections.[4]

Acoustics are another important part of exhaust system design. The sharp pressure pulses created by combustion generate high sound levels, which must be reduced to comply with Formula Student noise regulations. A muffler reduces this noise by controlling the behaviour of sound waves inside the exhaust. This can be achieved through expansion chambers, perforated tubes, packing material, and reflected wave paths. In simple terms, the muffler allows sound waves to interact in such a way that part of their energy is cancelled, absorbed, or dissipated before leaving the tailpipe. [2]

<img width="502" height="357" alt="image" src="https://github.com/user-attachments/assets/9e0d39ea-44a9-42c9-8c6c-491b4ec235ce" />

Figure 4: Exhaust Resonator

Resonators may also be used to target specific frequencies. These are designed to reduce undesirable tones or drone by reflecting certain sound frequencies back into the exhaust system. When the reflected wave is out of phase with the original sound wave, destructive interference occurs, reducing the amplitude of that frequency. This allows the exhaust to meet noise limits while avoiding excessive restriction.[5]

Overall, the science behind an exhaust system is based on controlling gas flow and pressure wave behaviour. A good Formula Student exhaust should remove combustion gases efficiently, minimise unnecessary pressure losses, maintain suitable gas velocity, improve scavenging over the desired engine speed range, and reduce noise without significantly restricting flow. The final design is therefore a compromise between performance, packaging, manufacturability, mass, heat management, and regulatory compliance.

## Difference between 4-2-1 and 4-1 exhaust types

The main difference between a 4-1 and a 4-2-1 exhaust system is the way in which the exhaust pulses from each cylinder are merged. In a 4-1 exhaust, all four primary runners merge directly into a single collector. This produces a shorter and more direct flow path, which is generally more effective at high engine speeds where the engine requires maximum flow capacity. As a result, 4-1 systems are often used on engines that are designed to operate near the top of the rpm range, such as high-speed race engines where peak horsepower is the main priority. However, this layout can produce a narrower power band, meaning the engine may only perform optimally over a smaller rpm range. [6]

<img width="587" height="245" alt="image" src="https://github.com/user-attachments/assets/43e33098-049c-40d9-ab50-520baf966f7b" />

Figure 5: 4-2-1 exhaust beside a 4-1 exhaust

A 4-2-1 exhaust merges the four primary runners into two secondary pipes before they finally merge into one outlet. This staged merging process allows the pressure pulses to be spread and tuned over a wider range of engine speeds. As a result, a 4-2-1 system is generally better suited for improving mid-range torque, throttle response, and drivability. This is particularly useful for Formula Student, where the engine is not constantly operating at maximum rpm. Instead, the car experiences frequent acceleration, braking, corner exits, and transient throttle conditions, meaning a wider and more usable torque band is more valuable than a small increase in peak power.[6]

For our Honda CBR600RR engine, a 4-2-1 exhaust was selected because it provides a more stable and usable exhaust characteristic across a wider rpm range. Although the CBR600RR is originally a high-revving motorcycle engine, its use in a Formula Student car requires strong response and consistent torque rather than simply maximum top-end horsepower. The 4-2-1 layout helps maintain exhaust gas velocity, improves scavenging over the mid-range, and reduces the likelihood of the engine becoming overly peaky. This makes the exhaust better suited to the operating conditions of the car, where drivability, acceleration performance, and predictable engine response are more important than achieving the highest possible peak power figure.[6]

## Design Constraints and FSUK Requirements

The exhaust system must be designed around both performance requirements and Formula Student UK scrutineering requirements. While the exhaust geometry affects flow restriction, pressure-wave tuning, scavenging, torque delivery, and engine response, the system must first be compliant with the relevant FSUK 2026 rules. For this reason, the exhaust was treated as a rules-constrained engineering component rather than only a performance part.

For FSUK 2026, the exhaust system is mainly governed by the internal combustion vehicle rules under CV3, Exhaust System and Noise Control. The first requirement concerns the position and direction of the exhaust outlet. Rule CV3.1.1 states that ‘the exhaust outlet must be routed to the side or rear of the vehicle” and positioned so that ‘the driver is not subjected to fumes at any speed considering the draft of the vehicle” [10]. This means that the exhaust outlet cannot be positioned in a way that allows exhaust gases to enter the cockpit area or flow directly towards the driver during running. For the Bruce exhaust, this requires the final outlet direction to be checked with the bodywork, rear structure, and expected airflow around the car.

The outlet position is also limited by rule CV3.1.2, which states that ‘the exhaust outlet(s) must not extend more than 450 mm behind the centerline of the rear axle” and must be ‘no more than 600 mm above the ground” [10]. This creates a clear packaging limit for the final tailpipe and muffler position. The exhaust therefore has to be routed so that the tailpipe remains within this rear overhang limit while still allowing enough length for the muffler, collector, lambda sensor position, and any serviceable joints.

Heat shielding is another major design constraint. Rule CV3.1.3 states that any exhaust components such as “headers, mufflers, etc.” which protrude from the side of the chassis in front of the rear axle must be shielded to prevent contact by people approaching the vehicle or by the driver exiting the vehicle [10]. The same rule also states that the outer surface temperature must not be harmful to a person touching it. This means that any exposed side-exit or side-mounted exhaust sections must be considered from a safety point of view, not only from a packaging point of view. For Bruce, the exhaust route must therefore be checked for accidental contact risk during driver egress, scrutineering, maintenance, and movement around the car.

The rules also restrict the method used for thermal protection. Rule CV3.1.4 states that the application of fibrous or absorbent material, for example “headerwrap”, to the outside of an exhaust manifold or exhaust system is prohibited [10]. As a result, heat management cannot rely on wrapping the headers. Instead, the design must use compliant heat shields, air gaps, suitable routing, material choice, and separation from sensitive components such as the fuel system, wiring, bodywork, and driver area.

The exhaust system must also satisfy the FSUK noise requirements. Rule CV3.2.1 states that the maximum sound level test speed is the engine speed corresponding to an average piston speed of 15.25 m/s, rounded to the nearest 500 rpm. The maximum allowed sound level up to this calculated speed is 110 dB(C), fast weighting [10]. For the 2003 Honda CBR600RR engine used in Bruce, the stroke is 42.5 mm. Using the mean piston speed equation,

<img width="287" height="32" alt="image" src="https://github.com/user-attachments/assets/5b10cf71-9955-4e3e-8601-f07ecb6c7605" />

the calculated test speed is approximately 10,765 rpm, which rounds to 11,000 rpm. The muffler and tailpipe must therefore be designed and tested with this speed in mind. This is important because an exhaust designed only for low restriction may fail the noise test, while an overly restrictive silencer may reduce engine performance.

The idle noise requirement must also be considered. Rule CV3.2.2 states that the idle test speed is determined by the team’s calibrated idle speed and that, at idle, the maximum allowed sound level is 103 dB(C), fast weighting [10]. If the idle speed varies, the vehicle may be tested across the full idle speed range determined by the team. This means that the engine calibration and exhaust design are linked: an unstable or excessively high idle could make the noise test more difficult to pass.

The inspection procedure also affects the exhaust design. The rules state that teams must bring a laptop to display engine speed measured by the ECU during the noise test, and that the sound measurement is taken using a free-field microphone positioned at exhaust outlet level, 0.5 m from the end of the exhaust outlet, at 45 degrees to the outlet in the horizontal plane [10]. This means the final outlet angle and location should be easy to access for scrutineering and should not be obstructed by bodywork, suspension, or other vehicle components.

If multiple exhaust outlets are used, the rules state that each outlet is tested and the highest reading is used [10]. Although the Bruce exhaust uses a single final outlet, this rule is still relevant when considering any future design changes involving twin exits or split mufflers. Any future exhaust design with more than one outlet would need to satisfy the noise limit at every outlet, not just as an average system reading.

The rules also state that if an exhaust has an active tuning or throttling device, it must comply with the rules in all positions. Manually adjustable devices must require tools to change and must not be moved after the noise test has been passed [10]. The Bruce exhaust does not currently use an active exhaust valve or adjustable noise device, which simplifies compliance. However, if a future team adds an adjustable baffle, valve, or insert, this requirement must be considered from the beginning of the design process.

In addition to the specific exhaust rules, the exhaust design must be checked against surrounding vehicle systems. The fuel system rules state that fuel spillage during refuelling must not contact the driver position, exhaust system, hot engine parts, or ignition system [10]. This affects the relative positioning of the exhaust, fuel tank, filler neck, venting, and any nearby hot surfaces. The exhaust must therefore be routed and shielded so that it does not create an ignition or heat hazard during refuelling, tilt testing, maintenance, or running.

From these rules, the main exhaust design constraints for Bruce are as follows:
• The outlet must be routed to the side or rear of the vehicle.
• The driver must not be exposed to exhaust fumes at any speed.
• The outlet must not extend more than 450 mm behind the rear axle centreline.
• The outlet must be no more than 600 mm above the ground.
• Any side-protruding exhaust components ahead of the rear axle must be shielded from accidental contact.
• The outer surface of any required shield must not be harmful to touch.
• Header wrap or other fibrous/absorbent wrapping material is not permitted.
• The exhaust must meet 110 dB(C) up to the calculated maximum sound test speed.
• The exhaust must meet 103 dB(C) at idle.
• The outlet must be accessible for the official microphone position during the noise test.
• Any future active or adjustable exhaust device must comply in all positions.
• The exhaust must be routed away from fuel spillage paths, fuel system components, wiring, bodywork, and the driver area.

Overall, the FSUK requirements define the minimum acceptable exhaust design. The final Bruce exhaust must therefore balance performance aims, such as scavenging and reduced restriction, with rules compliance, thermal safety, noise control, packaging, manufacturability, and serviceability. Passing scrutineering and noise testing is the first priority, as the car cannot compete dynamically unless the exhaust system satisfies these requirements. 

## Design Objectives

The exhaust system for Bruce was designed to satisfy several engineering objectives at the same time. While the exhaust must improve engine breathing and support the desired torque characteristics of the Honda CBR600RR engine, the first priority is that the system allows the car to pass scrutineering and operate reliably during Formula Student events. The design therefore had to balance performance, FSUK compliance, manufacturability, packaging, heat management, noise control, reliability, and serviceability. 

The main design objectives are summarised in Table 1. These onjectives were used to guide the selection of the 4-2-1 layout, pipe diameters, runner lenghts, collector positions, material choices, muffler selection, and manufacturing strategy.

Table 1: Main design objectives for the Bruce exhaust system.

<img width="672" height="765" alt="image" src="https://github.com/user-attachments/assets/a37feca7-5f76-46ef-b926-0de2e1960c91" />

<img width="676" height="315" alt="image" src="https://github.com/user-attachments/assets/1d4b5056-912a-41b5-b454-b260035f73e9" />

Overall, the objective was not simply to design the least restrictive exhaust possible. The final system had to be a practical Formula Student exhaust that could be manufactured by the team, fitted to Bruce, pass FSUK inspection and noise testing, and provide a usable engine characteristic for acceleration, autocross, and endurance. The best design was therefore the one that achieved the strongest compromise between performance, compliance, reliability, and build feasibility.

## Design Options and Concept Selection

Before finalising the exhaust design for Bruce, several possible exhaust layouts were considered. The purpose of this section is to compare the main design options and explain why the final 4-2-1 exhaust layout was selected. The exhaust system cannot be chosen based only on peak power, as the car must also satisfy FSUK rules, packaging limits, manufacturability, reliability, serviceability, and noise requirements. For a Formula Student car, a usable torque curve and predictable throttle response are often more valuable than achieving the highest possible peak power at very high engine speed.

The main concepts considered were:
• a 4-1 exhaust system,
• a 4-2-1 exhaust system,
• modifying or reusing the previous exhaust layout,
• using a mostly OEM-style motorcycle exhaust layout.

### Option 1: 4-1 Exhaust System

A 4-1 exhaust system merges all four primary runners directly into one collector. This layout is commonly used when the main aim is to improve high-rpm flow and maximise peak power. The shorter and more direct merge path can reduce complexity and may make the system easier to package compared with a longer staged exhaust.

The main advantage of a 4-1 system is that it can perform well at high engine speeds, where the engine requires strong flow capacity and where peak power is the main objective. This could be useful for a high-revving motorcycle engine such as the Honda CBR600RR, which was originally designed to operate at much higher engine speeds than many car engines.

However, a 4-1 exhaust usually produces a narrower tuned operating range. This means that the exhaust may perform strongly near the selected tuning speed but offer less benefit across the wider rpm range used during Formula Student events. Formula Student cars experience frequent acceleration, braking, corner exits, and transient throttle inputs. The engine is therefore not held constantly at peak rpm. For this reason, a narrow high-rpm powerband is less useful than a broader torque curve.

A 4-1 system was therefore not selected as the final concept. Although it may offer advantages for peak power, it was considered less suitable for Bruce because the design objective was to improve drivability, mid-range torque, and predictable response rather than only maximum top-end performance.

### Option 2: 4-2-1 Exhaust System

A 4-2-1 exhaust system first merges the four primary runners into two secondary pipes before merging into one final outlet. This staged merging process gives more opportunity to tune pressure-wave behaviour over a wider rpm range. Instead of focusing mainly on a single high-rpm tuning point, the 4-2-1 layout can support a broader and more usable torque band.

This is particularly suitable for Bruce because the car uses a 2003 Honda CBR600RR engine in a Formula Student application. Although the engine is capable of high rpm, the car benefits more from strong acceleration, stable torque delivery, and good throttle response than from a small increase in peak power. The 4-2-1 layout helps maintain exhaust gas velocity and supports scavenging over the mid-range, making the engine less peaky and more usable during acceleration, autocross, and endurance events.

The main disadvantages of a 4-2-1 system are increased manufacturing complexity and more difficult packaging. The system requires primary runners, two merge collectors, secondary pipes, a final collector, and a muffler section. Equalising runner lengths and maintaining good collector alignment is also more difficult than with a simpler layout. However, these disadvantages can be managed through CAD modelling, centreline length measurement, careful marking, and the use of manufacturing jigs.

For these reasons, the 4-2-1 system was selected as the preferred concept. It provided the best compromise between performance, drivability, FSUK suitability, and manufacturability for the Bruce car.

### Option 3: Modified Previous Exhaust Layout

Another option was to reuse or lightly modify the previous exhaust system. This would have reduced the amount of new manufacturing work required and may have allowed the team to save time during the build process. Reusing existing components can be a sensible design choice when the previous design is known to fit the car, has already been manufactured, and can be repaired or adapted with limited risk.

The main benefit of this option was manufacturability. Existing bends, collectors, and mounting points could potentially be reused, reducing the amount of sourcing, cutting, welding, and jig development required. It would also reduce the risk of delays caused by unusual pipe sizes or difficult-to-source components.

However, simply reusing the previous exhaust would not fully address the design objectives for Bruce. The previous geometry may not have been optimised for the desired torque range, equal runner lengths, serviceability, or current packaging requirements. Reusing an old design without recalculating and checking it would also make the design harder to justify during design review or FSUK design judging.

This option was therefore rejected as the main design route. Some existing knowledge and components could still be useful, but the exhaust geometry needed to be checked properly using calculations, CAD, and the current Bruce packaging constraints.

### Option 4: OEM-Style Motorcycle Exhaust Layout

An OEM-style motorcycle exhaust layout was also considered as a reference point. Since the engine originated from a Honda CBR600RR motorcycle, the original exhaust design provides a useful example of a working system for the engine. OEM exhausts are designed for reliability, packaging, noise control, and emissions compliance, which makes them valuable references.

However, the original motorcycle exhaust layout is not directly suitable for a Formula Student car. The packaging environment is completely different, as the engine is mounted in a custom chassis rather than a motorcycle frame. The outlet location, muffler position, heat shielding requirements, bodywork, driver position, fuel system, and scrutineering requirements are also different. In addition, an OEM motorcycle exhaust is not designed around the specific torque and drivability requirements of a Formula Student car.

For these reasons, the OEM layout was used only as a reference and was not selected as the final design concept.

### Concept Comparison

To support the final decision, the concepts were compared using the main exhaust design objectives. A higher score represents a better match to the requirement. The scores are not intended to be exact numerical performance values, but they help show the reasoning behind the final concept selection.

Table 2: Exhaust concept comparison matrix

<img width="735" height="379" alt="image" src="https://github.com/user-attachments/assets/5ce260b3-d606-4bdd-a7af-1dc2d9c7d0db" />

The 4-2-1 concept achieved the highest score because it best matched the overall requirements of the car. Although the 4-1 concept may offer stronger peak-power potential, it is less suited to the broader torque delivery required in Formula Student. The modified previous exhaust scored well for manufacturability and packaging, but it did not provide the same level of design justification or optimisation. The OEM-style layout was useful as a reference but was not suitable for the packaging and rules requirements of Bruce.

### Final Concept Selection

Based on the comparison, the final selected concept was a 4-2-1 exhaust system designed specifically for the Bruce car and the 2003 Honda CBR600RR engine. This layout was selected because it provides the best compromise between performance, drivability, manufacturability, packaging, and FSUK compliance.

The selected concept uses four primary runners from the exhaust ports, which merge into two secondary pipes before joining into a final tailpipe and muffler section. This staged layout supports a wider torque band and helps maintain exhaust gas velocity through the system. It also allows the exhaust to be tuned for a more useful operating range rather than focusing only on maximum high-rpm power.

The 4-2-1 layout also gives the team a clear engineering process to follow. The primary lengths, secondary lengths, pipe diameters, and collector positions can be selected using a combination of spreadsheet calculations, CAD modelling, available component sizes, and manufacturing constraints. This makes the design easier to justify and easier for future Powertrain members to understand.

The final concept was therefore chosen not because it was the simplest exhaust to manufacture, but because it gave the best overall solution for the car. It balanced the need for a usable engine characteristic with the practical requirements of Formula Student: passing scrutineering, meeting the noise limit, fitting within the chassis, being manufacturable by the team, and remaining serviceable during testing and competition.


## Engine Data and Calculation Inputs

Before the exhaust dimensions could be calculated, the key engine data for the Bruce powertrain had to be collected. The exhaust was designed around the 2003 Honda CBR600RR engine, which is a 599-600cc four-cylinder motorcycle engine. Since each primary runner only carries the exhaust flow from one cylinder, both the total engine displacement and the single-cylinder displacement are required for the exhaust sizing calculations.

The main engine data used in the exhaust spreadsheet is shown in Table 3. The values were taken from the 2003 CBR600RR service manual and used as the base inputs for the primary length, primary diameter, secondary diameter, tailpipe diameter, and FSUK noise-test speed calculations.

Table 3: Engine data and calculation inputs for the 2003 Honda CBR600RR exhaust.

<img width="650" height="708" alt="image" src="https://github.com/user-attachments/assets/97d94acf-15b5-42ba-8e85-bc1b3aecde07" />

The stroke value is particularly important because it determines the engine speed used for the FSUK noise test. The mean piston speed relationship is:

<img width="322" height="47" alt="image" src="https://github.com/user-attachments/assets/68758ac8-fa3f-4ba0-a05d-998c0b0bcc6c" />

Using a stroke of 42.5 mm and the FSUK piston speed value of 15.25 m/s gives a maximum test speed of approximately 10,765 rpm. This is rounded to the nearest 500 rpm, giving a final noise-test speed of 11,000 rpm. This value is not a performance target for the exhaust, but it is an important rules-compliance condition because the exhaust and muffler must be able to pass the static noise test up to this engine speed.

For the performance calculations, the desired peak torque speed was set to 6,000 rpm rather than the original motorcycle peak torque speed of approximately 11,000 rpm. This was done because Bruce is a Formula Student car rather than a road motorcycle. During acceleration, autocross, and endurance, the engine is not held constantly at maximum rpm. A broader and more usable mid-range torque band is more valuable than a narrow high-rpm power peak. Therefore, the exhaust calculations were based on improving drivability and useful torque delivery rather than only maximising top-end power.

The exhaust valve opening angle was also required for the primary runner length calculation. For the CBR600RR engine, the exhaust valve opening was taken as 40∘ before bottom dead centre. In the simplified spreadsheet method, the working exhaust duration was estimated as the exhaust valve opening angle plus 180∘, giving an approximate exhaust duration of 220∘. This value was then used in the empirical header length equations.

The tube wall thickness was set at 1.5 mm because exhaust tube is normally purchased using outer diameter and wall thickness rather than exact internal diameter. This is important because the flow calculations are based on internal diameter, while supplier selection and manufacturing are based on available outer diameter tube sizes. As a result, the calculated internal diameters had to be converted into realistic outer diameters that could actually be purchased and manufactured.

## Exhaust Calculation Results

Using the engine data from the previous section, the spreadsheet was used to estimate the required primary runner length, secondary runner length, primary diameter, secondary diameter, and tailpipe diameter. These calculations provided a theoretical starting point for the exhaust design. The final manufactured dimensions were then chosen by considering available tube sizes, packaging, weldability, collector availability, and the desired mid-range torque behaviour of the car.

### Primary Header Length

Two empirical equations were used to estimate the primary header length: the Smith equation and the Bell equation. The Smith equation gave a primary length of 293.6 mm, while the Bell equation gave a primary length of 355.6 mm. The average of these two values was then used as the target primary header length:

<img width="291" height="32" alt="image" src="https://github.com/user-attachments/assets/ea896bfa-0ef6-4b53-859c-018d8369bdb1" />

Therefore, the target primary header length used for the Bruce exhaust was approximately 325 mm. This value was treated as a design target rather than an exact fixed dimension, because the final geometry also had to account for the cylinder head flange, bend radii, merge collector position, packaging space, and manufacturability.

The secondary header length was estimated as approximately half of the primary length:

<img width="310" height="27" alt="image" src="https://github.com/user-attachments/assets/ad7df05e-b288-4806-a43e-6c4352a8b133" />

This gave an approximate secondary length of 162 mm. As with the primary runners, this value was used as a guide rather than an absolute value because the final secondary section also depended on the location of the first merge collectors and the final collector.

### Primary Header DIameter

The primary header diameter was calculated from the required primary tube area. The spreadsheet used the relationship:

<img width="371" height="31" alt="image" src="https://github.com/user-attachments/assets/f6e5d07f-e38d-4219-a256-d9fd29b56ba7" />

Using a desired peak torque speed of 6,000 rpm and a displacement of 36.61 cubic inches gave a calculated primary tube area of 0.623 square inches, equivalent to approximately 401.8 mm2. This corresponds to a calculated minimum internal diameter of 22.6 mm.

However, a tube with this exact internal diameter would not be ideal for the final design because exhaust tube must be selected from available outer diameters and wall thicknesses. The calculated minimum outer diameter, using a 1.5 mm wall thickness, was approximately 25.6 mm. For the final design, a larger internal diameter of 32 mm was selected. This gave a more practical tube size, reduced the risk of excessive restriction, and matched available exhaust tube dimensions more realistically.

### Secondary Pipe Diameter

The secondary pipe diameter was estimated from the combined area of two primary runners. If two equal primary pipes merge into one secondary pipe, the equivalent theoretical diameter can be approximated by:

<img width="195" height="27" alt="image" src="https://github.com/user-attachments/assets/619fef42-f392-419f-9b5d-65245fd950e6" />

Using two 32mm internal diameter primary runners: 

<img width="301" height="26" alt="image" src="https://github.com/user-attachments/assets/7b874967-5888-4d2c-9c4d-a89a21f31263" />

This gave a theoretical secondary internal diameter of approximately 45.3 mm. The final selected secondary internal diameter was 42 mm. This is slightly smaller than the theoretical equal-area value, but it helps maintain exhaust gas velocity, which can support scavenging and mid-range torque. The design therefore accepts a small reduction in area in exchange for stronger gas velocity and more practical component availability.

### Tailpipe Diameter

The final tailpipe diameter was estimated by combining the flow area of the two secondary pipes. Using the same area-based method, the spreadsheet gave a theoretical final tailpipe internal diameter of approximately 59.4 mm.

The final selected tailpipe internal diameter was 52 mm. This is smaller than the theoretical equal-area value, giving an area ratio of approximately 0.77 compared with the theoretical diameter. Since velocity is inversely proportional to area, the smaller 52 mm tailpipe increases gas velocity compared with the theoretical equal-area pipe.

This was considered acceptable because the design aim was not only to minimise restriction, but also to maintain useful exhaust gas velocity for scavenging and mid-range torque. In addition, the smaller tailpipe was cheaper, easier to package, and easier to source than a larger-diameter final section.

### Summary of Calculated and Selected Dimensions

Table 4: Summary of calculated and selected exhaust dimensions

<img width="657" height="398" alt="image" src="https://github.com/user-attachments/assets/5c60d93d-0fa3-4eb4-b825-4322d5c51cca" />

Overall, the spreadsheet calculations were used as a starting point rather than as fixed final dimensions. The calculated values provided a theoretical target, while the final selected dimensions were chosen by balancing performance, gas velocity, packaging, supplier availability, cost-effectiveness, and manufacturability. This approach is appropriate for a Formula Student exhaust because the best design is not simply the largest or least restrictive system, but the system that gives the best compromise between flow, scavenging, noise control, packaging, and practical manufacture.

## CAD Development and Design Iterations

The exhaust CAD model was developed by first assessing the geometry of the previous exhaust design. The purpose of this stage was to understand how the existing runner lengths compared with the calculated target values from the spreadsheet, and to identify where the design could be improved for the Bruce car.

The primary runners were measured along the centreline of each pipe rather than using a straight line distance between the exhaust valve and the collector. This is important because the exhaust gases follow the curved path of the pipe. Each bend therefore contributes to the effective runner length and must be included as an arc length rather than ignored as a direct point-to-point distance. The end of the primary runner was taken as the point where the pipe begins to expand into the secondary diameter, as this is where the pressure wave sees the first major change in cross-sectional area.

<img width="366" height="220" alt="image" src="https://github.com/user-attachments/assets/1f6f8fd5-df7d-4024-abe4-c32ec4d56665" />

Figure 6: Centreline used to measure the effective exhaust runner length. The blue arrow shows where the primary length measurement ends.

The original CAD geometry showed that the primary runners were longer than the ideal value calculated in the spreadsheet. The target primary length was approximately 324.6 mm. For exhaust ports 1 and 4, the original measured centreline length was approximately 382.5 mm, meaning it was around 57.9 mm longer than the target value. For exhaust ports 2 and 3, the original measured centreline length was approximately 422.0 mm, making it around 97.4 mm longer than the target value.

There was also a difference of roughly 39.4 mm between the two sets of primaries. This was not ideal because unequal runner lengths can cause the exhaust pulses to arrive at the collector at slightly different times. Since the exhaust design aims to use pressure-wave tuning, large differences in primary length can result in different cylinders being tuned for slightly different engine speeds.

<img width="737" height="717" alt="image" src="https://github.com/user-attachments/assets/db50eaba-d432-463d-be14-1c274ba92833" />

Figure 7: First two measurements of the old exhaust primaries for cylinder 1 and 4.

<img width="571" height="721" alt="image" src="https://github.com/user-attachments/assets/94597e63-d63b-4828-8dce-a0a925f51be2" />

Figure 8: Next three measurements of the old exhaust primaries for cylinders 1 and 4.

<img width="562" height="736" alt="image" src="https://github.com/user-attachments/assets/f6631f3c-fe3d-451a-ac16-0f9eaa5a64e3" />

Figure 9: Last three measurements of the old exhaust primaries for cylinders 1 and 4.

<img width="517" height="722" alt="image" src="https://github.com/user-attachments/assets/ef69a862-af1a-4dea-81b0-91931f9d3122" />

Figure 10: First three measurements of the old exhaust primaries for cylinders 2 and 3.

<img width="540" height="752" alt="image" src="https://github.com/user-attachments/assets/931694f4-60bf-4c72-8b03-ab1f37dc28ea" />

Figure 11: Last three measurements of the old exhaust primaries for cylinders 2 and 3.

From this CAD assessment, the main design changes required were identified. The redesigned primary runners needed to be shorter, closer to the spreadsheet target length, and more consistent between cylinder pairs. The number of bends also needed to be reduced where possible, as each bend adds manufacturing complexity and can introduce additional flow losses.

Another design aim was to keep the end of each primary runner at a similar height before entering the secondary section. This helps reduce flow disruption when the two primary runners merge and makes the transition into the secondary pipe more consistent. It also improves the practicality of manufacturing and aligning the merge collector.

Overall, the CAD development stage showed that the previous exhaust geometry was useful as a reference, but that it was not ideal for the new Bruce exhaust design. The final design therefore retained the useful packaging knowledge from the previous model while changing the primary runner geometry to better match the calculated target lengths and improve consistency between cylinders.

## Final Exhaust Design for Bruce

The final exhaust design for Bruce was developed from the CAD iteration process described previously. The aim was to produce a practical 4-2-1 exhaust system for the 2003 Honda CBR600RR engine, with primary runner lengths as close as possible to the calculated target of 324.6 mm. The final design also had to provide clearance around the engine, use manufacturable bend angles, and allow the primary runners to merge cleanly into the secondary section.

<img width="357" height="312" alt="image" src="https://github.com/user-attachments/assets/3c39f47b-ab9d-43a1-aee6-447dbf4bbcdb" />

Figure 12: Final redesigned exhaust primaries for the Bruce exhaust system.

For exhaust ports 1 and 4, the first short straight section from the exhaust outlet was changed to 41.5 mm. This dimension was selected to give clearance to the oil filter on the engine. A 60-degree bend was then used, giving an arc length of 20.94 mm. This bend was angled down to help route the pipe towards the merge collector while maintaining the required packaging clearance.

After the first bend, a 14 mm straight section was added, followed by a 45-degree bend with an arc length of 25.71 mm. A 109.6 mm straight pipe section was then used, followed by another 45-degree bend with an arc length of 25.71 mm. Finally, a 92 mm straight pipe segment was added at the end of the primary runner.

Together, these sections produced a total primary length of 329.46 mm for exhaust ports 1 and 4. This is only 4.86 mm away from the spreadsheet target length of 324.6 mm. This difference was considered acceptable because the value is very close to the target and because perfect CAD dimensions are difficult to reproduce exactly during fabrication.

For exhaust ports 2 and 3, the redesigned primary runner begins with a 70 mm straight pipe from the exhaust outlet. This is followed by a 30-degree bend with a centreline arc length of 18.33 mm. A second 50 mm straight section is then used, followed by another 30-degree bend with a centreline arc length of 18.33 mm. The final section is a 164.5 mm straight pipe leading towards the adaptor region.

This gives a total primary length of approximately 321.16 mm for exhaust ports 2 and 3. This is only 3.44 mm away from the spreadsheet target length of 324.6 mm. As with cylinders 1 and 4, this difference was considered acceptable because it is small compared with the overall primary length and is within a realistic manufacturing tolerance for a hand-fabricated exhaust system.

The final primary runner dimensions are summarised in Table 5.

Table 5: Final primary runner lengths compared with the calculated target.

<img width="737" height="86" alt="image" src="https://github.com/user-attachments/assets/b5209422-0c2e-4a7a-b0ed-0d7fb805b218" />

Although the final design uses different pipe geometries for the outer and inner cylinders, both geometries were adjusted to achieve almost the same target length. This is important because the exhaust system is intended to make use of pressure-wave tuning. For this effect to work consistently, the reflected pressure wave should return to each cylinder at approximately the correct point in the engine cycle. Keeping the primary lengths close to equal helps make the exhaust pulses more consistent between cylinders and reduces the chance of one cylinder pair being tuned differently from the other.

The selected final design is also more practical to manufacture than a fully custom theoretical exhaust. It uses standard bend angles, straight pipe sections, and expansion adaptors rather than requiring complex custom collectors for every transition. This makes the design more realistic for Formula Trinity to manufacture in-house while still remaining close to the calculated target dimensions.

Overall, the final Bruce exhaust design represents a compromise between theoretical exhaust tuning, packaging around the Honda CBR600RR engine, oil filter clearance, manufacturability, and expected fabrication tolerance. The primary lengths are significantly closer to the calculated target than the previous exhaust geometry, and the final design provides a clearer and more justifiable engineering basis for the manufactured system.

## Material Selection

Material selection was an important part of the Bruce exhaust design because the exhaust system operates in a high-temperature, high-vibration, and corrosive environment. The selected materials had to provide suitable heat resistance, corrosion resistance, weldability, availability, and manufacturability while still being realistic for the team to source and fabricate.

For the Bruce exhaust, different stainless steel grades were used in different sections of the system. This was done because each section of the exhaust has slightly different requirements. The primary runners are closest to the cylinder head and experience the highest temperatures and most severe heat cycling. Further downstream, the secondary pipes, merge collectors, and tailpipe still need to withstand exhaust temperature and vibration, but the thermal loading is generally less severe than at the primaries.

<img width="690" height="455" alt="image" src="https://github.com/user-attachments/assets/031dee7b-6303-4e2f-93a5-3da60a99379c" />

Figure 13: Comparison between 316 and 316L stainless steel.

The primary runners were manufactured from 316L stainless steel. Grade 316L is a low-carbon stainless steel alloy with strong corrosion resistance and good weldability. The low carbon content helps reduce carbide precipitation during welding, which helps maintain corrosion resistance around the weld joints. This is useful for a custom exhaust system because the primary runners require several welded joints and bends. The addition of molybdenum also improves resistance to pitting and chloride corrosion, making 316L suitable for environments where moisture, road contaminants, or high humidity may be present.

Although 304 stainless steel is more common and more economical for many automotive exhaust systems, 316L was selected for the primaries because it provides better corrosion resistance and good weld quality. This made it a suitable choice for the most thermally demanding and fabrication-sensitive part of the exhaust. For extreme continuous high-temperature racing or turbocharged applications, 321 stainless steel may be more suitable due to its improved heat cycling stability. However, for the naturally aspirated Honda CBR600RR engine used in Bruce, 316L was considered an appropriate material for the primary runners.[8]

<img width="757" height="285" alt="image" src="https://github.com/user-attachments/assets/c9821be7-7d07-45ed-8974-149b65bcb54e" />

Figure 14: Comparison between 304 and 409 stainless steel.

The secondary pipes and merge collector sections were made from 304 stainless steel. Grade 304 is one of the most commonly used stainless steels for exhaust systems due to its good corrosion resistance, availability, weldability, and general suitability for high-temperature exhaust applications. This made it a practical choice for the larger sections of the system, where standard
exhaust components and bends were easier to source.[8]

The tailpipe section was made from 409 stainless steel. Grade 409 does not have the same corrosion resistance or surface finish quality as 304 or 316L, but it is widely used in production automotive exhaust systems because it is durable, suitable for exhaust temperatures, and more cost-effective. Since the tailpipe is further downstream from the engine and is less thermally demanding than the primary runners, 409 stainless steel was considered acceptable for this section.[9]

Table 6: Material selection for the Bruce exhaust system.

<img width="640" height="345" alt="image" src="https://github.com/user-attachments/assets/d63fb5ea-5427-4b66-befc-9ac170a3396e" />

Material selection was not limited only to the main pipe sections. Smaller supporting components such as exhaust flanges, sleeves, and gaskets are also essential to the performance and reliability of the finished system. These components should be treated as part of the exhaust design rather than as afterthoughts, because a well-designed pipe layout can still fail if the joints do not seal correctly or cannot be serviced easily.

<img width="695" height="207" alt="image" src="https://github.com/user-attachments/assets/31bc3d70-9316-4b15-9160-b743eb5a24ce" />

Figure 15: Exhaust flanges, sleeves, and gaskets used for assembly and sealing.

Flanges are needed to connect the exhaust securely to the cylinder head and to allow the system to be removed for inspection, repair, or engine access. Sleeves and slip joints can help with assembly and alignment, especially in a hand-fabricated exhaust where small manufacturing tolerances are unavoidable. These joints also make the exhaust easier to service, as sections of the system can be removed without cutting or permanently modifying the pipework.

Copper exhaust gaskets should be used at the cylinder head interface because they provide a good sealing surface and can help fill small imperfections between the exhaust flange and the engine. This is important for preventing exhaust leaks. Exhaust leaks can reduce engine performance, affect lambda sensor readings, increase noise, and create unnecessary heat around the engine bay. They can also make fault-finding more difficult because incorrect lambda readings may appear to be a fuelling issue when the real cause is air entering through a leaking exhaust joint.

Overall, the chosen material combination provides a practical balance between performance, durability, corrosion resistance, weldability, supplier availability, and cost-effectiveness. The use of 316L stainless steel for the primaries gives the most critical section of the exhaust strong corrosion resistance and weld quality, while 304 and 409 stainless steels provide practical solutions for the downstream sections. Including the smaller components in the material selection process also helps ensure that the final exhaust is not only manufacturable, but also reliable, serviceable, and suitable for Formula Student use.

## Component Availability and Supplier Constraints

After the theoretical exhaust dimensions were calculated, the next stage was to check whether the required tube sizes, bends, adaptors, and merge collectors could realistically be sourced and manufactured. This was an important part of the design process because the final exhaust geometry could not be based only on ideal spreadsheet values or CAD dimensions. The design also had to account for available outside diameters, wall thicknesses, bend radii, delivery times, supplier availability, and the practicality of manufacturing the system using the tools available to the team.

The exhaust dimensions calculated in the spreadsheet were therefore treated as design targets rather than fixed values. In practice, exhaust tubing is normally purchased using outside diameter and wall thickness, while the exhaust calculations are based mainly on internal diameter and flow area. This means that the selected components had to be checked against both the theoretical flow requirements and the available real-world tube sizes.

For the final tailpipe section, a 54 mm outside diameter 90-degree stainless steel bend was selected from FMIC. This component is suitable for the final section of the exhaust, where the flow from all four cylinders has already merged and a larger pipe diameter is required. For the secondary section, a 45 mm outside diameter 90-degree stainless steel bend was selected from Speeding Parts. This section is used after the two primary pairs have merged, but before the final collector and tailpipe.

The primary runners were more difficult to source because the design required smaller 35 mm outside diameter tubing with specific bend angles. The final primary design uses 30-degree bends for cylinders 2 and 3, and 60-degree bends for cylinders 1 and 4. Swiss Fittings was identified as a suitable supplier for these more specialist stainless-steel bend angles. For the 45-degree bends required in 35 mm outside diameter tubing, Amazon Ireland was also considered as a practical option depending on availability and delivery time.

Straight stainless-steel tube sections for the required diameters can be sourced locally from Amari in Dublin. This is useful because straight tube is generally easier to obtain than pre-formed bends, and local sourcing reduces shipping time and delivery uncertainty. However, the selected exhaust diameters are not especially common for exhaust fabrication in Ireland. In particular, 35 mm, 45 mm, and 54 mm outside diameter tubing are relatively uncommon sizes in the local market. These sizes are more closely associated with Japanese motorcycle and performance exhaust applications, which makes it difficult to find Irish suppliers that stock matching bends or offer accurate mandrel bending for these diameters.

For this reason, the selected purchasing strategy was to source the specialist bends from online exhaust or stainless-fitting suppliers, while sourcing straight tube locally where possible. This provided the best compromise between manufacturability, availability, lead time, and keeping the final exhaust close to the calculated CAD geometry. It also avoided the need for custom mandrel bending, which would likely have been more expensive, slower, and harder to arrange for the selected non-standard diameters.

Table 7: Supplier selection for the Bruce exhaust components.

<img width="656" height="460" alt="image" src="https://github.com/user-attachments/assets/e1e080f6-cc74-405a-9b03-07ddd61fee54" />

The merge collectors were one of the most difficult components to source. The smaller 35–45 mm outside diameter merge collectors were reused from the previous exhaust system because no suitable European supplier could be found at the time. For the larger 45–55 mm outside diameter merge collector, a suitable component was eventually found on eBay. However, this component had to be shipped to Paula, who was the Powertrain Lead at the time, in Germany before being forwarded to Ireland.

Although this solved the issue for the current exhaust build, it is not a repeatable or ideal purchasing process for future teams. For future exhaust designs, supplier research for merge collectors should be completed before the exhaust geometry is finalised. This is especially important when non-standard pipe diameters are being used, because the availability of merge collectors may strongly influence the final geometry, manufacturing cost, and project timeline.

Overall, component availability had a direct influence on the Bruce exhaust design. The selected geometry was not based only on theoretical optimum dimensions, but also on what could be realistically sourced, cut, welded, and assembled by the team. This makes the final design more practical and reduces the risk of delays during manufacturing. Future teams should repeat this availability check early in the design process, especially if changing pipe diameters, collector sizes, or supplier locations.

## Manufacturing Preparation: Drawings and Jigs

Once the exhaust geometry had been finalised in CAD, the next stage was to prepare the design for manufacture. This was necessary because the exhaust is not manufactured as one continuous part, but from several individual bends, straight pipe sections, reducers, adaptors, and merge collectors that must be cut, aligned, and welded together accurately.

Small errors in pipe length, bend angle, rotation, or alignment can quickly build up across the full exhaust system. This is especially important in the primary runners, where the pipe length is directly linked to the exhaust tuning calculations. For this reason, the manufacturing preparation focused on two main areas: producing clear technical drawings and designing jigs for the most alignment-critical sections of the exhaust.

<img width="891" height="582" alt="image" src="https://github.com/user-attachments/assets/6f769027-f22b-481a-8bc9-32236fba50b5" />

Figure 16: Full exhaust assembly drawing showing labelled components

<img width="807" height="745" alt="image" src="https://github.com/user-attachments/assets/9dcda18b-df5c-4c11-9a33-4e37a307125b" />

Figure 17: Labelled primary runners showing the individual cut sections.

The full assembly drawing was produced to show the overall exhaust layout, including the primary runners, merge collectors, secondary pipes, tailpipe, and silencer section. This drawing allows the fabricator to understand how the complete system fits together before looking at the individual parts.

A separate labelled primary drawing was also created to identify each cut section of the primary runners. This is important because the 4-2-1 layout relies on the correct pairing of cylinders and consistent primary lengths. The primaries from cylinders 1 and 4 have a different geometry from the primaries from cylinders 2 and 3, so clearly identifying each section reduces the chance of cutting, positioning, or welding the wrong pipe segment.

<img width="775" height="642" alt="image" src="https://github.com/user-attachments/assets/62abaeac-efe6-43e7-ab76-02e19d3ad2c5" />

Figure 18: Example technical drawing used during manufacturing.

Individual technical drawings were produced for the main exhaust sections. These drawings included the required pipe lengths, bend angles, diameters, and tolerances needed for cutting and assembly. By separating the exhaust into smaller drawings, the manufacturing process becomes easier to follow and the risk of mixing up pipe sections is reduced.

Table 8: Main drawings used during exhaust manufacturing preparation.

<img width="653" height="330" alt="image" src="https://github.com/user-attachments/assets/5621a3a2-3301-4ec8-a060-3f99f6debadb" />

<img width="877" height="295" alt="image" src="https://github.com/user-attachments/assets/f8598991-0dc9-46bb-96e2-96cd091eea39" />

Figure 19: Assembly and labelled primary drawings used during manufacturing preparation.

<img width="846" height="257" alt="image" src="https://github.com/user-attachments/assets/704e734f-e793-46aa-843c-bcba7ef96679" />

Figure 20: Technical drawings for the primary runner geometries.

<img width="855" height="271" alt="image" src="https://github.com/user-attachments/assets/a700c064-c5ea-4763-86c2-56358dbbb87a" />

Figure 21: Exhaust valve connection and tailpipe drawings.

Jigs were used for the sections where repeatability and alignment were most important. The purpose of a jig is to hold pipe sections in the correct position during cutting, tack welding, and final welding. This is particularly useful for the primary runners because they need to remain close to the calculated target length while also meeting the merge collectors at the correct angle and height.

If the primaries are manufactured with different lengths or enter the collector at different angles, the exhaust pulses may not behave consistently between cylinders. This could reduce the effectiveness of the pressure-wave tuning and make the collector harder to weld. Jigs were therefore used to control the most important alignment points without making the fabrication process too restrictive.

<img width="637" height="581" alt="image" src="https://github.com/user-attachments/assets/c258a654-29dc-44f1-8da5-bafec5aab8dc" />

Figure 22: Welding jig used to hold pipe sections in position during cutting, tack welding, and final welding.

Four 3D-printed jigs were designed for the exhaust manufacturing process. The holes in the jigs were made slightly larger than the pipe outside diameters to provide clearance. This was necessary because real pipe sections will not fit perfectly into an exact CAD-sized hole, especially after cutting, bending, and deburring. The clearance allows for small manufacturing tolerances while still guiding the pipe sections into the correct position.

Table 9: Jigs used during exhaust manufacturing.

<img width="691" height="234" alt="image" src="https://github.com/user-attachments/assets/43b7ba3b-84bb-4971-93f2-4b7095b282f6" />

The merge collector jigs were especially important because the two primary pipes must meet the collector at the correct angle, height, and spacing. A smoother transition into the collector helps reduce flow separation, improves weld access, and reduces the chance of a mismatch between the two primary pipes.

A jig was not used for the 60-degree connection on primaries 1 and 4. Although this section is important, it was judged that a rigid jig would not guarantee an accurate final fit because small variations in cutting, bend radius, rotation angle, and weld gap could prevent the pipe from sitting correctly. Instead, this section was left adjustable during fabrication so that the fabricator could make small corrections during fit-up. This approach gives more flexibility and reduces the risk of forcing the pipe into an inaccurate position.

Overall, the use of technical drawings and targeted jigs improves the manufacturability of the exhaust system. The drawings provide a clear reference for pipe lengths, diameters, bend angles, and assembly order, while the jigs help control the most critical alignment points during fabrication. Some final adjustment will still be required during welding and fitting to the car, but the combination of detailed drawings and jigs gives the best chance of producing an exhaust that matches the CAD model and remains close to the theoretical dimensions calculated in the spreadsheet.

## Marking Out and Manufacturing Process

The first stage of the manufacturing process is to accurately mark out each pipe section before cutting. This step is important because the exhaust is made from several individual bends and straight sections, and small errors in length can quickly affect the final fit-up, primary length accuracy, and collector alignment. Before marking any pipe, the outside diameter should be checked using callipers to confirm that the correct tube size is being used. This is especially important when working with multiple pipe diameters, such as the primary, secondary, and tailpipe sections, as the bends can look similar once they are separated from their packaging.

Once the correct pipe has been identified, the required cut positions should be marked using a scribe and a metal ruler. A scribe is preferred over a marker because it produces a fine scratch on the metal surface, making the cut line more accurate and less likely to rub off during handling. A metal ruler is also recommended, as it provides a straight and rigid reference when measuring short pipe sections. The marked lengths should be taken directly from the technical drawings and should match the naming system used in the CAD model, drawings, and jig layout.

<img width="826" height="226" alt="image" src="https://github.com/user-attachments/assets/cc6f38a9-2a05-48e4-be75-86a1c94630a2" />

Figure 23: Callipers, metal ruler and a scribe used for measuring out the pipes accurately.

A particular difficulty with the pipes used in this build was that many of the purchased components were pre-bent sections with excess straight pipe on either side. This meant that the straight sections had to be measured from the point where the bend begins, rather than from the end of the purchased component. To estimate the start of the bend, a straight ruler can be placed along the outside of the pipe on the side where the bend curves inward. The ruler is then slid along the straight section until it begins to lift away from the pipe surface. This lifting point gives a practical approximation of where the bend begins. From this point, the required straight-line length can be measured and marked using the ruler and scribe.

<img width="737" height="466" alt="image" src="https://github.com/user-attachments/assets/a0d6401c-50c8-40aa-b374-31717e3e2220" />

Figure 24: Measuring Out Station in the Workshop.

This process should be repeated for each required pipe section, including all primary segments and bend sections. Each component should be marked carefully before any cutting takes place. It is also useful to label the pipe sections immediately after marking so they can be matched back to the drawing. This is particularly important for the primary runners, as cylinders 1 and 4, and cylinders 2 and 3, use different geometries and should not be mixed up.

<img width="501" height="357" alt="image" src="https://github.com/user-attachments/assets/830d77fe-5cdc-4a0f-9238-953752ba7172" />

Figure 25: Image of a Metal Chop Saw.

After all sections have been marked, the pipes can be cut using a metal chop saw. This gives a cleaner and more repeatable cut than attempting to cut the sections by hand. During cutting, appropriate personal protective equipment should be worn, including eye protection and hearing protection. The process is very loud, and metal swarf can be ejected from the cutting area. Long sleeves and high-collar clothing are also recommended to reduce exposure to hot metal particles, provided they are suitable for workshop use and do not create an entanglement risk.

When cutting the pipe, the saw blade should be positioned on the waste side of the scribed line rather than directly on the line. This is because the blade has a finite thickness, meaning it removes material as it cuts. Cutting directly on the line can therefore make the finished part shorter than intended. Where possible, it is better to leave a small amount of excess material on the pipe. This provides a safety margin if the marking or cutting process is slightly inaccurate and allows the part to be trimmed down later.

<img width="431" height="442" alt="image" src="https://github.com/user-attachments/assets/c2a5464e-322e-4566-baac-39104bb8adca" />

Figure 26: Double checking length segment of pipe.

Once the pipe has been cut, the length should be checked against the drawing using callipers or a ruler, depending on the required accuracy. If a section is too long, it can be gradually reduced using an angle grinder or other suitable finishing method. Material should be removed in small increments, approximately 1 mm at a time, until the pipe reaches the desired length and tolerance. This method is slower than cutting directly to the final length, but it reduces the risk of making the part too short and having to remake it.

<img width="621" height="345" alt="image" src="https://github.com/user-attachments/assets/a8f26e1c-c0f2-4b31-a790-ecf9b3f39b68" />

Figure 27: Drawings made on the wooden board to ease the direction and positioning of the parts.

As each pipe section is completed, it should be labelled according to the technical drawing. This avoids confusion during assembly, especially when multiple pieces have similar diameters or bend angles. For this build, the cut pipe sections were also laid out on a large sheet of wood in their approximate assembly positions and labelled accordingly. This acted like a physical puzzle board, allowing each component to be placed in the correct order and orientation before welding. This approach is highly recommended because it makes the manufacturing sequence easier to visualise and helps identify any missing or incorrectly cut parts before the welding process begins.

Once all primary pipe sections have been cut, checked, labelled, and laid out in the correct order, the secondary and tailpipe sections can be prepared. In this design, the secondary length is mainly formed by the 90-degree bend and the length through the merge collector. No dedicated jig was produced for this section because the final height and location of the completed primaries cannot be predicted perfectly due to manufacturing tolerances, weld gaps, cutting errors, and small angular deviations during assembly. For this reason, the secondary bends should be cut to suit once the primaries have been completed and their final position is known. This does introduce some inaccuracy into the final secondary length, but it is a more practical and manageable approach than forcing the secondary section to match an ideal CAD position that may no longer be achievable after fabrication.

The tailpipe sections can be cut more accurately because their geometry is less dependent on the final position of the primaries. However, the design should still consider where the exhaust disconnects from the muffler section. This is important because the lambda sensor should ideally be positioned in the fixed section of pipe connected to the tailpipe rather than in a removable or unsupported section. The exact sensor location and disconnect point should therefore be considered during manufacturing, depending on how the exhaust alignment develops during welding.

<img width="382" height="472" alt="image" src="https://github.com/user-attachments/assets/83e64efb-2ac4-4e5e-8500-406ab6dfc135" />

Figure 28: Welded Segment of a pipe for 1&4 primary.

Once the pipe sections have been prepared, the exhaust can move into the welding stage. At this point, the aim is to tack-weld the system first, check the fitment on the car, confirm the collector alignment, secondary routing, tailpipe position, and sensor access, and only then proceed with final welding. Good preparation during the marking and cutting stage makes the welding process significantly easier and improves the chance of producing an exhaust that matches the CAD design, calculated runner lengths, and practical vehicle packaging requirements.

## Validation and Testing Plan

The exhaust system must be validated before the car is used for dynamic testing or competition. The purpose of the validation plan is to confirm that the manufactured exhaust fits the Bruce car, is mechanically secure, does not leak, manages heat safely, meets the FSUK noise requirements, and does not negatively affect engine operation. Since the exhaust is positioned close to the engine, chassis, bodywork, wiring, fuel system, and driver area, the system must be tested gradually rather than only checked at the final scrutineering stage.

The first stage of validation should be a static fitment inspection. Before the engine is started, the full exhaust should be installed on the car and checked against the CAD model, engine position, chassis tubes, suspension, bodywork, fuel system, and driver area. Particular attention should be given to the primary runners, merge collectors, lambda sensor position, muffler location, tailpipe direction, and all serviceable joints. The exhaust outlet should be checked to make sure that it is routed to the side or rear of the car, does not direct fumes towards the driver, does not extend beyond the permitted rear limit, and remains accessible for the official noise-test microphone position.

The second stage should be a mechanical security inspection. All flanges, sleeves, springs, clamps, brackets, welds, and mounting points should be checked before running the engine. The system should not be able to contact the chassis, engine mounts, bodywork, wiring, coolant hoses, fuel lines, or the driver area when it is moved by hand. Any area with insufficient clearance should be corrected before testing because exhaust movement increases significantly when the engine is running.

Once the exhaust has passed the static inspection, a low-temperature leak check should be carried out. The engine should be started and allowed to idle while the team checks for exhaust leaks around the cylinder head flanges, primary joints, collectors, lambda bung, muffler joints, and tailpipe connection. Any ticking noise, visible soot mark, hot gas jet, or unstable lambda reading should be treated as a possible leak. The engine should not be revved hard until all leaks have been fixed, as leaks can increase noise, damage nearby components, and give incorrect lambda sensor feedback to the ECU.

The next stage should be a heat and clearance test. The engine should be brought up to operating temperature while the exhaust route is inspected from a safe distance. Nearby hoses, wiring, bodywork, fuel system components, and driver-contact areas should be monitored for heat exposure. After shutdown, the system should be allowed to cool before close inspection. Any discolouration, melting, smell of hot plastic, damaged sleeving, or excessive surface temperature near an accessible area should be treated as a failure. Since external header wrap is not permitted, any heat issue should be solved using compliant heat shields, air gaps, rerouting, or improved separation from sensitive components.

A pre-competition noise test should then be carried out using the same method as closely as possible to the FSUK static noise test. For the 2003 Honda CBR600RR engine, the calculated maximum sound-test speed is approximately 11,000 rpm. The exhaust must therefore be tested at idle and progressively up to this speed using the ECU rpm display. The sound meter should be positioned at exhaust outlet level, 0.5 m from the end of the outlet and at 45 degrees to the outlet in the horizontal plane. The target is to remain below 103 dB(C) at idle and below 110 dB(C) at the required maximum test speed. If the exhaust fails or is close to the limit, the muffler design journal should be reviewed and additional attenuation, repacking, a revised muffler, or an upstream resonator should be considered before competition.

After the static tests, the exhaust should be validated during controlled running. The car should first complete short low-load runs while the team listens for rattling, check for contact marks, and confirms that the exhaust remains secure. The run length and engine load should then be increased gradually. After each run, the exhaust should be inspected for loose fasteners, cracked welds, soot mark, bracket movement, damaged mounts, or signs of heat damage. If available, lambda readings, engine temperature, throttle response, and driver feedback should also be recorded. Any change in engine behaviour after fitting the exhaust should be investigated before longer endurance-style running.

Table 10: Exhaust validation and testing plan.

<img width="572" height="652" alt="image" src="https://github.com/user-attachments/assets/ea5ade43-2791-4ef9-9ec8-70c9a23efb00" />

<img width="573" height="552" alt="image" src="https://github.com/user-attachments/assets/c812ead9-12d0-4124-84f3-03d820715719" />

The validation plan should be treated as a staged process. Passing one test does not remove the need for later inspection, because exhaust problems often appear only after heat cycling, vibration, or extended running. The most important results to record are the static noise readings, the engine speed used during the noise test, any leak locations, any heat shielding changes, and any failures found after running.

## Risks, Issues, and Future Improvements

Although the Bruce exhaust design was developed using spreadsheet calculations, CAD modelling, supplier research, technical drawings, and manufacturing preparation, several practical issues were identified during the design and build process. Recording these issues is important because it allows future Formula Trinity members to learn from the project and avoid repeating the same mistakes.

One of the largest issues encountered was the difference between the engine CAD model and the real Honda CBR600RR engine. The engine CAD model used during the exhaust design was downloaded from an online source and was assumed to be sufficiently accurate for packaging checks. However, during physical fitment it became clear that the CAD model was not a perfect representation of the real engine. As a result, some components that appeared to fit correctly in SolidWorks did not fit correctly when installed on the actual engine.

This created a significant manufacturing and assembly problem. Since the mismatch was only discovered during physical assembly, some modifications had to be implemented at short notice without the same level of drawing preparation, CAD checking, or jig support as the original design. The team also found it difficult to determine exactly which part of the CAD model was inaccurate. The issue could have originated from the engine geometry, mounting position, exhaust flange location, oil filter position, surrounding components, or a combination of several small dimensional differences. This meant that some improvements and modifications had to be carried out directly during fabrication.

A 3D-printed mock-up of the exhaust was also produced to help verify the design before final manufacture. This proved valuable because it allowed the team to physically inspect the exhaust route and identify potential clearance issues before committing fully to the stainless steel components. However, during this inspection the team focused primarily on the clearance issue around primaries 1 and 4. As a result, the clearance problems affecting primaries 2 and 3 were not identified early enough. This demonstrated that a mock-up is only effective if the inspection process is systematic and covers the entire assembly rather than concentrating only on the first issue that is discovered.

This was an important lesson for future projects. When using 3D-printed mock-ups, jigs, or prototype components, the inspection process should follow a structured checklist. Every primary runner, merge collector, flange, mounting point, and surrounding component should be checked before the design is approved for manufacture. Particular attention should be given to oil filter clearance, engine movement allowance, chassis clearance, bodywork clearance, fuel system proximity, wiring routes, welding access, and serviceability. Future teams should avoid assuming that a single identified issue is the only problem present in the design.

Another issue encountered during manufacturing was that some last-minute modifications were more difficult because not every revised section had a corresponding updated drawing. Drawings are important because they allow components to be reproduced, checked, repaired, and understood by future team members. If changes are made during fabrication but the CAD model and drawings are not updated afterwards, the final manufactured exhaust may no longer match the documented design. Future teams should therefore ensure that any manufacturing changes are fed back into the CAD model and technical drawings once the final geometry has been confirmed.

The old exhaust system also contained a feature that may be worth investigating for future vehicles. Located shortly after the merge collectors were several small muffler-like sections or expansion chambers. These components may have acted as small resonators, helping to control pressure-wave behaviour, reduce unwanted reflections, and smooth the exhaust flow after the collector region.

In an exhaust system, pressure waves are generated whenever the exhaust valves open and close. These waves reflect from changes in cross-sectional area, collector junctions, and the end of the exhaust system. A carefully designed resonator or expansion chamber may help manage these pressure waves by reducing undesirable reflections and improving overall flow behaviour. Such components may also provide additional noise attenuation while maintaining acceptable backpressure characteristics.

The exact purpose of these sections on the old exhaust was not fully analysed during the Bruce redesign, and therefore they were not included in the final design. However, they represent a potentially valuable area for future development. Future teams should investigate whether these components were originally intended for noise reduction, pressure-wave tuning, packaging reasons, or manufacturing convenience. Their effectiveness could be assessed through noise measurements, lambda stability, transient throttle response, simulation studies, and dyno testing where available.

The main risks, issues, and recommended improvements are summarised in Table 11.

Overall, the main lesson from the Bruce exhaust project is that CAD models, 3D-printed mock ups, and jigs should be treated as design aids rather than guarantees of physical fitment. For future exhaust systems, the team should verify the engine model against the real engine, inspect every part of the mock-up systematically, measure critical dimensions directly from the vehicle, and update the CAD model whenever manufacturing changes occur. This would reduce the amount of last-minute fabrication work and improve confidence that the final exhaust matches the documented design.

Future teams should also investigate the possible use of resonators or small expansion chambers after the merge collectors. If designed correctly, these may help with pressure-wave control, flow stability, and noise reduction. However, their effectiveness should be confirmed through testing and analysis rather than simply copying features from previous designs. The best future exhaust design will combine verified CAD data, physical measurements, practical manufacturing methods, and testing results to create a system that performs reliably both on paper and on the car.

Table 11: Main exhaust risks, issues, and future improvements.

<img width="510" height="741" alt="image" src="https://github.com/user-attachments/assets/9b50a796-e616-4d47-92fe-3e9d1f8dbad7" />

## References

[1] Wikipedia, Exhaust System, Available at: https://en.wikipedia.org/wiki/Exhaust_system (Accessed on 30/05/2026)

[2] Karim Nice, How Mufflers Work, Available at: https://auto.howstuffworks.com/muffler1.htm (Accessed on 30/05/2026)

[3] Turn14 Distribution, The Science of Exhaust: Expert Education from Burns Stainless, Available at: https://news.turn14.com/2018/07/16/the-science-of-exhaust-expert-education from-burns-stainless/ (Accessed on 30/05/2026)

[4] Trevor Anderson, Performance Exhaust System Design And Theory, Available at: https://www.enginelabs.com/features/performance-exhaust-system-design-and-theory/ (Accessed on 30/05/2026)

[5] Walker, What Does a Resonator Do?, Available at: https://www.walkerexhaust.com/support/exhaust-101/what-does-a-resonator-do.html (Accessed on 30/05/2026)

[6] Redline360, 4-1 vs 4-2-1 Headers- What is the difference? What makes more power?, Available at: https://shop.redline360.com/blogs/whats-the-latest/4-1-vs-4-2-1-headers-what-is-the-difference-what-makes-more-power (Accessed on 30/05/2026)

[7] Eric Siedlarz, Excel Spreadsheet, Available at: Formula Trinity Folder, (Accessed on 30/05/2026)

[8] Burns Stainless, Stainless Steels for Exhaust Systems- Comparing 304/321 and More, Available at: https://burnsstainless.com/blogs/articles-1/stainless-steels-for-exhaust-systems (Accessed on 30/05/2026)

[9] Summit Racing Equipment, What is the difference between 304 and 409 stainless steel?, Available at: https://help.summitracing.com/knowledgebase/article/SR-03932/en-us (Accessed on 30/05/2026)

[10] IMech, Formula Student 2026 Rules, Available at: https://www.imeche.org/docs/default-source/1-oscar/formula-student/2026/rules/fsuk-2026-rules—v1-09e21118e54216d0c8310ff0100d05193.pdf?sfvrsn=2 (Accessed on: 04/06/2026)





























