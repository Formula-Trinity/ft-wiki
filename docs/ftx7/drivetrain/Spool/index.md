# Spool

## Spool Overview

A spool is essentially the opposite of a differential. A differential allows the car's rear wheels to rotate at different speeds (which they have to on corners), while a spool forces both rear wheels to spin at the same rate.

The main reasons for opting to use a spool were:

- Cost (cheaper than a differential)
- Weight (lighter than a differential)
- Not an off-the-shelf part (more to discuss with judges at competition)

The decision to opt for a spool did lead to significant knock-on effects in other departments, which is expanded on in their respective wiki pages. The main department impacted was suspension, who implemented a high roll centre, decreased rear track width and jacking in order to combat the lack of differential action.


## Spool Design Considerations

When designing a spool, the main thing to take into account is the torque that the engine will subject the spool to. This torque can be calculated using the max engine torque (in this case, 64 Nm from a CBR600RR, which is easily found by googling a spec sheet), and multiplying this torque value by the engine's primary gear ratio (spec sheet), gear ratio in first gear (again, spec sheet; 1st gear because this is the gear with highest torque), and the final drive ratio (number of driven sprocket teeth / number of drive sprocket teeth).

Any spool design made must be able to withstand the calculated torque. The shear stress on the spool cross section (likely a solid cylinder) can be easily calculated with the following formula:

**τ_max = 16T / (πd³)**

Remember the spool is in **shear**, so use the shear yield strength of the selected material, not tensile strength, to check if it's strong enough.

The minimum diameter for a spool can be calculated using the above formula. Keep in mind that this minimum diameter should be excluding any dowel/key holes needed for assembly. If the minimum diameter comes out to be 30 mm, then there should be 30 mm of uninterrupted material carrying the torque.

A factor of safety of about 2.0 is preferable for critical components like this.

Any dowels/keys for joining assembly parts should have shear and bearing calculations carried out to ensure they are strong enough.

Designing a spool to fail at the dowels rather than the shaft is preferable, i.e. have the dowels fail before the shaft shears, but have them both strong enough.

There are plenty of YouTube videos for designing slotted shaft keys, taking into account things such as shock factor (which increases stress on keys).


## FTX-7 Spool — What Could Be Done Better Next Time?

The spool was designed out of 7075-T6 aluminium, which is a strong aluminium alloy but not that stiff, so it is not ideal for a shaft. It was manufactured out of 6061 due to an error, which is absolutely too weak.

In future, steel should be used. Not mild steel, as it is probably also too weak. Some form of heat-treated steel would be ideal.

In the FTX-7 spool, the minimum torque-carrying cross section had keyholes in it. This isn't good practice, so the diameter should be increased.

The spool consisted of a three-part assembly held together with keys in a slotted shaft. Flanges were located on either side for CV, sprocket and brake disc mounting. Two keys were used to secure each flange.

In future, maybe one (much stronger, of course) key should be used. Loose tolerances can lead to only one key being engaged at a time, which leads to a lot of stress on one and very little on the other. Using one key would eliminate this uncertainty.


## Engineering Drawings

The drawings used for manufacturing the FTX-7 spool are shown below. They are a good example of designing for manufacturing, and its impact on the price of a part.

The initial quoted price for this assembly was €300, and through changing tolerances and making small feature changes, the final quoted price was €150 — a 50% reduction in cost with no performance trade-off (or really any visible differences between the two designs).

The design-for-manufacturing choices made to have this impact are detailed below.


### Spool Shaft

![FTX-7 Spool Centre](../../../assets/images/ftx7/Spool%20Centre.png)

Standard g6 shaft tolerance was used for the section of the shaft that had to slide into bearings to ensure a snug fit, and that the spool and inner bearing race spun together.

However, there was no need for the shaft to have a tight tolerance on the section between the bearings, so the diameter of this section was increased and given no shaft tolerance callout, reducing machining time and hence cost.

Largest cross section is 30mm, meaning the part could potentially be made from a stock 30mm diameter piece of steel (no guarantee, but would reduce machining time if so)

Appropriate shaft tolerance (F9) on key holes, not unnecessarily tight, not too loose. F9 hole and a f9 key (Chosen spool key tolerance) leaves a max clearance between key and slot of 0.144mm, which is adequate. 

There are lots of online tools to figure out these kinds of tolerances, i found [MESYS ISO Fit and Tolerance Calculator](https://www.mesys.ch/calc/tolerances.fcgi?lang=en) particularly helpful because it's easy to use and quite visual.

The .50mm x 45 edge chamfers on the slots are to ensure the part assembles nicely, essentially deburring sharp edges from machining. The MAX notation basically tells the machinist that the dimension isn't that important, just don't remove more than .50mm. Without the MAX, the machinist would have to ensure that 0.50 +/- 0.05 was removed, which is more time and more money.

The inner radius on the key slots (.30 MAX) is there simply because making a 90 degree slot isn't possible here. The slots will be end milled, and a round end mill can't produce a 90 degree sharp edge, hence the radius. MAX again tells the machinist the dimension here isn't critical, just not too round.


### Left Spool Flange

![FTX-7 Left Spool Flange](../../../assets/images/ftx7/Spool%20Flange%20Left.png)

Most of the mentioned DFM choices mentioned for the spool shaft apply here. Don't hesitate to use section views to show features in your drawings.

Holes for bolts should be made 0.5mm oversized (M10 bolt -> 10.5mm hole) to ensure bolt actually fits (doesn't thread the hole, damage part)

The 4 holes on this part are for CV joint mounting. No crazy tolerance really needed here, because we already had the off the shelf part in hand, and could measure it and knew the part would come out within tolerance. Keep in mind if you're designing a part to fit with an off the shelf/custom part that you don't have yet (you only have a technical drawing) you may need to have a +/- tolerance here.


### Right Spool Flange

![FTX-7 Right Spool Flange](../../../assets/images/ftx7/Spool%20Flange%20Right.png)

Nearly exactly the same as above. Brake disk and CV joint mounting in this case.


### Spool Key

![FTX-7 Spool Key](../../../assets/images/ftx7/Spool%20Key.png)

Despite the assembly needing 4 keys, only one key was manufactured.

The key was manufactured as one length, and angle grinded in house. This reduced machining time and replaced it with an operation we can easily carry out ourself that didn't require tight tolerance.

Chamfers on the edges of this dowel are good practice (Recall our .30 MAX inner radius on slots, a .50mm x 45 chamfer will never interfere with this)

F9 key tolerance was chosen for reasons discussed already in spool shaft section


