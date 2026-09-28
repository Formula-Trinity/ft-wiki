# Oil Sump

## What is a Wet Sump Lubrication System and Why is it Needed?

A wet sump lubrication system is a system where the engine oil is stored in a pan or sump at the bottom of the engine. The oil pump draws oil from this sump through a pickup pipe and then delivers pressurised oil to the engine’s bearings, crankshaft, camshafts, pistons, timing system, and other moving components.

The lubrication system is essential because it reduces friction between moving parts, removes heat from loaded components, reduces wear, and helps protect the engine from mechanical damage. Without a reliable oil supply, the metal surfaces inside the engine would make direct contact with each other, causing rapid overheating, wear, and possible engine failure.

In a road motorcycle, the original wet sump is designed for the expected operating conditions of the bike. However, when the same engine is used in a Formula Student car, the oil system is exposed to different loading conditions. The car can experience strong braking, acceleration, and cornering, which can cause the oil inside the sump to move away from the pickup. This is known as oil surge.

If the oil pickup becomes uncovered, the oil pump may draw air instead of oil. This can cause a
sudden reduction in oil pressure and a loss of the protective oil film inside the engine. Even short
periods of oil starvation can damage bearings and other highly loaded components.

A dry sump system is often used in racing applications to reduce this problem, but it adds cost,
mass, complexity, external oil lines, an external tank, and additional packaging work. For this
reason, the first design approach considered for Bruce was a baffled wet sump. A baffled wet sump
can improve oil control while keeping the system relatively simple, low-cost, and manufacturable.

## Why Oil Baffles are Needed in a Formula Student Car

Oil baffles are internal plates or walls placed inside the sump to control the movement of oil.
Their main purpose is to keep oil close to the pickup during dynamic driving conditions. In a
Formula Student car, the sump may experience oil movement in several directions:

• During braking, oil moves towards the front of the sump.

• During acceleration, oil moves towards the rear of the sump.

• During cornering, oil moves towards the outside of the turn.

• During combined braking and cornering, oil can move diagonally away from the pickup.

If this oil movement is not controlled, the pickup can become uncovered. This can cause a drop
in oil pressure and allow air to enter the lubrication system. Even a short period of oil starvation
can be harmful because the engine bearings rely on a continuous pressurised oil film.

The baffle system does not stop oil from moving completely. Instead, it slows the movement of
oil away from the pickup and encourages oil to return to the pickup area. A common solution is
to use a central pickup cell surrounded by fixed baffle walls. Small transfer holes or slots allow
oil to drain back into the central cell, while preventing the full oil volume from rapidly escaping
during cornering, braking, or acceleration.

The purpose of the baffles is therefore not mainly to prevent oil from spilling out of the sump.
The sump should already be sealed. The real purpose is to prevent oil surge inside the sump and
reduce the chance of oil starvation.

## Design Objectives

The main design objectives for the oil sump review are listed below:

• Maintain oil coverage around the pickup during braking, acceleration, and cornering.

• Reduce the risk of oil starvation and sudden oil pressure drop.

• Keep the design simple enough to manufacture using the team’s available tools and skills.

• Avoid excessive added mass.

• Allow oil to drain back into the pickup area after dynamic manoeuvres.

• Avoid blocking the oil pickup or restricting the oil pump supply.

• Maintain sufficient clearance between the baffles, windage tray, crankshaft, and moving
parts.

• Allow the sump to be cleaned, inspected, and checked after any modification.

• Use a material that is suitable for welding, vibration, and engine oil temperatures.

• Avoid unnecessary modification if the original sump geometry is already suitable.

• Validate the final decision through oil pressure testing.

The design therefore had to balance oil control, manufacturability, reliability, serviceability, and
packaging. A very complex design could improve oil control but would be harder to manufacture
and inspect. A very simple design would be easier to manufacture but may not provide enough
protection against oil surge. The final decision therefore depended not only on theory, but also
on physical inspection of the actual sump.

## Design Options and Concept Selection

Several design options were considered for improving oil control in the sump. At the start of the
design process, the main concern was that oil could move away from the pickup during braking,
acceleration, and cornering. For this reason, different baffle and sump modification options were
compared before the sump was physically inspected.

Table 1: Oil sump design option comparison

<img width="667" height="755" alt="image" src="https://github.com/user-attachments/assets/70ff19e5-fd8b-4aba-b146-f7f15c585067" />

Before removal, the preferred concept was a fixed baffle system with a central pickup cell. However,
after inspecting the sump, it was found to be narrow and tall, meaning the oil naturally stays
close to the pickup rather than spreading across a wide, shallow pan.

As a result, the risk of oil moving away from the pickup was lower than expected. Since adding
baffles would introduce extra manufacturing time and risks such as weld distortion, debris,
restricted drain-back, or leaks, the final decision was to keep the standard sump and validate it
through oil pressure testing.

## Physical Inspection of the Existing Sump

After the initial baffle concept was developed, the oil sump was removed from the Honda
CBR600RR engine for physical inspection. This inspection was important because the original
design work was based on the assumption that the sump may behave like a wide, shallow oil
pan, where oil could easily move away from the pickup during cornering, braking, or acceleration.
Once the sump was removed, it became clear that the actual sump geometry was relatively
narrow and tall.

<img width="602" height="502" alt="image" src="https://github.com/user-attachments/assets/573c9c55-d848-44ab-9c9a-04cfcef2ab57" />

Figure 1: Internal view of the Honda CBR600RR sump after removal from the engine, showing the narrow and deep geometry that helps keep oil close to the pickup region.

This is beneficial for oil control because the oil is contained in a deeper, more compact volume.
Instead of being able to move a large distance sideways or longitudinally, the oil remains more
concentrated around the lower part of the sump and therefore closer to the oil inlet and pickup
region. This changed the design decision.

Although internal baffles could still be manufactured, the benefit of adding them was no longer
considered large enough to justify the risks involved. Welding inside the sump could create
distortion, leave debris inside the oil system, restrict oil drain-back, or cause sealing issues. Anyof these issues could reduce reliability rather than improve it.

For this reason, the final design decision was not to modify the sump for the current car. The
selected solution is to retain the standard Honda sump geometry and focus on careful inspection,
correct oil level, and oil pressure validation during engine testing. This is still a valid engineering design outcome. The design process showed that the simplest and most reliable option was to avoid an unnecessary modification, while keeping the theoretical baffle design documented for
future members if further oil control is required

## Theoretical Oil Sump Baffle Design

Although the final decision for Bruce was to retain the standard sump, the theoretical baffle
design is still useful for future development. If oil pressure testing shows pressure drops during
braking, acceleration, or cornering, this baffle concept should be reconsidered.

The theoretical sump design uses a nested cell layout. The oil pickup is placed in a central
cell, with fixed baffle walls surrounding it on all four sides. The left and right baffles reduce oil movement during cornering, while the front and rear baffles reduce oil movement during braking
and acceleration.

<img width="720" height="457" alt="image" src="https://github.com/user-attachments/assets/d2567693-2258-420d-ad12-7e5ab20f0afe" />

Figure 2: Theoretical top-down layout of the proposed sump baffle system, showing the central
pickup cell, surrounding baffle walls, oil pickup location, and approximate sump dimensions.

The baffle system is designed so that oil can still return to the pickup area. This is achieved
using small lower transfer holes or slots in the baffle plates. These openings allow oil to drain
back into the central pickup cell, but they restrict the rate at which oil can rapidly escape from
the pickup area during dynamic manoeuvres.

<img width="862" height="372" alt="image" src="https://github.com/user-attachments/assets/bf9b4381-355e-44df-963e-8f1e63833103" />

Figure 3: Theoretical longitudinal section of the sump, showing the approximate oil level, pickup
pipe, windage tray position, lower transfer slots, and drain-back holes.

The central pickup zone is the most important part of the design. The pickup should remain
covered by oil during normal operation and during short periods of high acceleration. To improve
this, a raised standpipe collar could be included around the pickup. This collar would act as
a small reserve region around the pickup and help prevent the pickup from being uncovered
immediately when oil moves to one side of the sump.

The approximate sump dimensions used for the theoretical baffle design are:

L = 230mm

W = 160mm

D = 95mm

<img width="792" height="480" alt="image" src="https://github.com/user-attachments/assets/8128ef74-c1e5-4748-a1c3-ac7b33b9d22b" />

Figure 4: Theoretical transverse section of the sump, showing the narrow sump width, oil level,
central pickup region, and lower transfer slot arrangement.

The baffle plates would be manufactured from 2–3 mm aluminium sheet. The proposed outer
baffle wall would be positioned approximately 16 mm inside the sump wall. This would create
an outer reserve region while still keeping the main oil volume controlled around the pickup.

The pickup tube should have a sufficient internal diameter to avoid restricting the oil pump. A
pickup bore of approximately 16–18 mm is proposed. The pickup inlet should be positioned
approximately 5 mm above the sump floor to reduce the risk of blockage from the floor while
still allowing the pump to draw from the lowest practical oil level. A pickup screen should also
be used to reduce the chance of debris entering the oil pump.

<img width="741" height="472" alt="image" src="https://github.com/user-attachments/assets/2087f5d0-261a-4323-81d9-553ff92e779a" />

Figure 5: Theoretical windage tray layout, showing the main pickup opening and proposed
drain-back holes.

A simple windage tray could also be included above the oil surface. The windage tray would
help reduce oil being whipped up by the rotating crankshaft and help direct oil drain-back. A
possible design would use 1.5 mm aluminium sheet with drain-back holes. The holes should be
positioned so that oil can return to the sump while still allowing the tray to act as an additional
barrier during braking.

This theoretical design was not manufactured for the current car because the physical sump
inspection showed that the original sump geometry was already narrow and tall. However, the
design remains a useful future reference if oil pressure validation suggests that the standard sump
is not sufficient.

## CAD Development and Packaging

The CAD model should be used if the sump is modified in the future. The purpose of the CAD
work would be to confirm that the baffles, pickup, windage tray, and sump body can fit together
without interference. The most important checks would be:

• Clearance between the baffle walls and the sump walls.

• Clearance between the windage tray and the crankshaft or rotating assembly.

• Clearance between the pickup inlet and the sump floor.

• Position of the central pickup cell relative to the oil pickup.

• Position and size of the transfer holes or slots.

• Access for welding, inspection, and cleaning.

• Access to the drain plug and oil pickup screen.

The CAD should include a top-down plan view of the sump, a front section view through the
pickup cell, and a side section view showing sump depth, oil level, pickup height, windage tray
position, and drain-back holes. The design should also be checked against the installed engine
position in the car.

This is important because the car may experience oil movement in a different direction depending
on the installed engine angle. The baffle layout should therefore be reviewed in the same
orientation as the engine is mounted in Bruce. For the current car, CAD modification of the
sump was not required because the final decision was to retain the standard sump. However,
these checks should be followed if the baffle concept is developed in a future season.

## Material Selection and Theoretical Manufacturing Process

If the sump is modified in the future, the proposed baffle material is 6082-T6 aluminium. This
material is suitable because it has a good strength-to-weight ratio, is commonly available, and
is weldable compared with stronger but less weldable aluminium grades. The baffles should be
made from 2–3 mm aluminium plate, which provides enough stiffness without adding unnecessary
mass. The theoretical sump baffles would be manufactured using the following general process:

1. Remove the sump from the engine and fully drain the oil.
   
2. Clean the sump thoroughly to remove oil residue before any cutting or welding.
   
3. Measure the internal sump dimensions and confirm the pickup position.

4. Mark out the baffle plate profiles on 2–3 mm aluminium sheet.
  
5. Cut the baffle plates to shape.
  
6. Drill or cut the lower transfer holes and deburr all edges.
  
7. Trial fit the baffles inside the sump and check pickup clearance.
  
8. Tack weld the baffles into position.
  
9. Re-check the pickup position, transfer holes, and windage tray clearance.
  
10. Fully weld the baffles to the sump floor and side walls.
  
11. Inspect all welds for cracks, gaps, or poor fusion.
  
12. Clean the sump again to remove swarf, weld debris, and contamination.
  
13. Fit the pickup tube and pickup screen.
  
14. Refit the sump using a suitable gasket or sealant method.

After welding, the sump must be carefully cleaned. Any aluminium swarf, weld debris, or loose
material left inside the sump could enter the oil system and damage the engine. Cleaning and
inspection are therefore critical parts of the manufacturing process. For the current Bruce sump,
this manufacturing process was not carried out. The sump was inspected and left unmodified
because the existing narrow and tall geometry was considered suitable at this stage.

## Current Sump Inspection, Cleaning, and Refit Process

As the final decision was to retain the standard sump, no internal baffle manufacturing was
carried out. The main work required was inspection, cleaning, and refitting of the original sump.
The sump should be removed from the engine carefully and drained fully before inspection. Once
removed, the inside of the sump should be checked for oil residue, metallic debris, cracks, damage,
or signs of previous impact.

The oil pickup area should also be inspected to make sure that it is clear and that there is no
blockage or contamination around the inlet. The sump should then be cleaned thoroughly before
refitting. Any old gasket material or sealant should be removed from the mating surfaces without
damaging the aluminium. The sealing face should be checked to make sure it is flat and free
from scratches or dents.

The sump can then be refitted using the correct gasket or sealant method. After refitting, the
engine should be filled with the correct amount of oil and checked for leaks. The drain plug and
sump joint should be inspected before the engine is started. Once the engine is run, oil pressure
should be monitored to confirm that the standard sump provides a reliable oil supply.

## Filling, Inspection, and Leak Checking Procedure

Before the engine is run, the sump must be checked carefully. The first stage is a visual inspection.
The sump body, pickup tube, pickup screen, drain plug, gasket surface, and surrounding engine
area should all be checked for damage or contamination. The sump should then be fitted to the
engine and filled with the correct amount of oil.

During filling, the team should check that there are no external leaks from the sump gasket,
drain plug, or any nearby oil system connection. A static leak check should be carried out before
starting the engine. The car should be left stationary with oil in the sump, and the sump should
be inspected for any signs of dripping, wet joints, or oil marks.

Any leak should be treated as a failure and corrected before the engine is started. Once the static
check has passed, the engine can be cranked or run at low speed while monitoring oil pressure.
Oil pressure should build quickly and remain stable. If oil pressure does not build, or if the
pressure fluctuates heavily, the engine should be stopped immediately and the sump, pickup, and
oil system should be inspected.

## Validation and Testing Plan

The validation plan is intended to confirm that the standard sump can supply oil reliably during
realistic Formula Student operating conditions. Although the sump was not modified, validation
is still important because the final decision depends on the original sump geometry being suitable
for the car.

Table 2: Oil sump validation and testing plan.

<img width="622" height="672" alt="image" src="https://github.com/user-attachments/assets/4074d50d-412e-44d1-a387-02db4cb731ef" />

The most important validation result is oil pressure stability. If the oil pressure remains stable
during braking, acceleration, and cornering, this supports the decision to retain the standard
sump. If the oil pressure drops during dynamic manoeuvres, this suggests that the pickup may
still be uncovering or that oil is not remaining close enough to the pickup. In that case, the
theoretical baffle design should be revisited as a future improvement.

## Risks, Issues, and Future Improvements

The main risks and future improvements for the oil sump system are shown in Table 3.

Table 3: Oil sump risks, issues, and future improvements.

<img width="472" height="695" alt="image" src="https://github.com/user-attachments/assets/ce8e73f2-d51c-436d-9309-11dc1a76e8b2" />

<img width="472" height="155" alt="image" src="https://github.com/user-attachments/assets/a5a21452-2691-4133-acbf-be22eb60fa41" />



























