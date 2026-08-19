# Spool

## Spool Overview
A spool is essentially the opposite of a differential. A differential allows the car's rear wheels to rotate at different speeds (which they have to on corners), while a spool forces both rear wheels to spin at the same rate.

The main reasons for opting to use a spool were:
Cost (cheaper than a differential)
Weight (Lighter than a differential)
Not an off the shelf part (More to talk about to judges at competition)

The decision to opt for a spool did lead to significant knock-on effects in other departments, which is expanded on in their respective wiki pages. The main department impacted was suspension, who implemented a high roll centre, decreased rear track width and jacking in order to combat the lack of differential action.

## Spool design considerations
When designing a spool, the main thing to take into account is the torque that the engine will subject the spool to. This torque can be calculated using the max engine torque (In this case, 64Nm from a CBR600RR, this is easily found by googling a spec sheet), and multiplying this torque value by the engine's primary gear ratio (spec sheet), gear ratio in first gear (again, spec sheet. 1st gear because this is the gear with highest torque), and the final drive ratio (number of driven sprocket teeth / number of drive sprocket teeth). 

Any spool design made must be able to withstand the calculated torque. The shear stress on spool cross section (likely a solid cylinder) can be easily calculated with the following formula: 

τ_max = 16T / (πd³)

Remember the spool is in **shear**, so use the shear yield strength of the selected material, not tensile to check if it's strong enough.

The minimum diameter for a spool can be calculated using the above formula. Keep in mind that this minimum diameter should be excluding any dowel/key holes needed for assembly. if the minimum diameter comes out to be 30mm, then there should be 30mm of uninterrupted material carrying the torque.

A factor of safety of about 2.0 is preferable for critical components like this.

Any dowels/keys for joining assembly parts should have shear and bearing calculations carried out to ensure they are strong enough

Designing a spool to fail at the dowels rather than the shaft is preferable. i.e. have the dowels fail before the shaft shears, but have them both strong enough.

There are plenty of youtube videos for designing slotted shaft keys, taking into account things such as shock factor (which increases stress on keys).

## FTX-7 Spool, what could be done better next time?
Was designed out of 7075-T6 aluminium, which is a strong aluminium alloy but not that stiff, so not ideal for a shaft. (Was manufactured out of 6061 due to error which is absolutely too weak)
In future, steel should be used. Not mild steel, it is probably also too weak. Some form of heat treated steel ideal.
In FTX-7 spool, the minimum torque carrying cross section had keyholes in it. This isn't good practice, so diameter should be increased.

Three part assembly held together with keys in a slotted shaft. Flanges either side for CV, sprocket and brake disk mounting.
Two keys were used to secure each flange.

In future, maybe one (much stronger of course) key should be used. Loose tolerances can lead to one key only being engaged at a time sometimes, which leads to a lot of stress on one and very little on the other. Using one key would eliminate uncertainty.
