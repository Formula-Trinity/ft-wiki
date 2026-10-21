# General Manufacturing Principles

Design each part around the way it will be made. Formula Trinity has limited workshop equipment, so decide during design whether a part can be made in-house or must be outsourced.

## Choose the process

Start by asking what the part begins as.

| Starting material and method | Guide |
| --- | --- |
| Flat sheet, cut and folded | [Bent Sheet Metal](./processes/sheet-metal-bent.md) |
| Several sheet or plate pieces, welded | [Welded Sheet Metal](./processes/sheet-metal-welded.md) |
| Tube, box section, angle or flat bar | [Tube & Box-Section Weldments](./processes/tube-box-weldments.md) |
| Externally milled solid stock | [CNC Milling](./processes/cnc-milled.md) |
| Externally turned round stock | [Lathe Parts](./processes/lathe-parts.md) |

Use the appropriate SolidWorks Sheet Metal or Weldments workflow for fabricated parts. Generic solid bodies can hide flat patterns, cut lengths and joint details needed for manufacture.

For mixed assemblies, model each component using its own manufacturing process, then bring the components together in an assembly. Account for weld size, access and interference where relevant.

## Jigs and fixtures

Plan a jig or fixture during design when:

- components must be held accurately during welding
- a hole pattern must align with a mating part
- repeatability matters across several parts
- welding distortion is likely
- a part is difficult or unsafe to hold

Include dedicated fixtures in the CAD assembly where practical. Printed drill guides, tack-welding locators, marking templates and bend gauges are useful low-cost aids. Keep printed fixtures away from prolonged welding heat.

For a jig printed with a 0.4 mm nozzle, the FTX7 build used approximately 0.4 mm clearance around holes and locating features as a starting point. Test critical features on the actual printer.

## Tolerances

Specify tolerances that the chosen process can achieve.

### In-house fabrication

| Process | FTX7 working guidance |
| --- | --- |
| Length cut with an angle grinder | About ±3 mm, approximately ±1–2 mm with a marked line and template |
| Hole position drilled by hand | About ±3 mm with a printed drill guide, ±5 mm or worse without one |
| Manually welded assembly | Avoid overall tolerances tighter than about ±3 mm without a suitable fixture |

Make interfaces insensitive to normal fabrication error. Use clear datums, sensible clearance holes, and slots only where adjustment is useful. For example, an 11 mm or slotted hole may suit a non-critical M10 bolt's clearance. Confirm the required edge distance and joint function before use.

### Outsourced machining

Use a sensible general tolerance. The FTX7 working default was **ISO 2768-mK**, unless the drawing deliberately specifies another standard. Apply tighter tolerances only to functional features. Use standard engineering fits where required, particularly for bearing bores and shafts.

For every tight tolerance, identify what fails if the dimension is relaxed. Unnecessary precision increases machining and inspection cost.

## Design for cost

- Use readily available [stock sizes](./workshop-reference/materials-stock.md).
- Reuse materials and thicknesses across parts.
- Prefer one folded component over several welded pieces where practical.
- Choose stock close to the finished component's dimensions to reduce material removal, machining time and waste.
- Keep outsourced parts compact and machinable in few setups.
- Remove non-functional machined surfaces and decorative features.
- Reuse brackets, hole patterns, jigs and templates where appropriate.

## Release check

Before releasing a component, confirm:

- the manufacturing process and responsible manufacturer are known
- the CAD workflow matches the process
- the required tools, stock and access are available
- tolerances are achievable and functionally justified
- any jig, template or fixture has been designed
- weld access, weld size and distortion have been considered
- the part cannot be simplified or combined with another
- another team member could manufacture it from the drawing

Record lessons from the finished part. They also support the [Design for Manufacture judging topic](../../competition/statics/design/design_for_manufacture.md).
