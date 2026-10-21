# Bent Sheet Metal

Use this process when a part starts as flat sheet and gains its shape mainly through cutting and folding. Typical parts include guards, brackets, firewalls, enclosures and battery boxes.

If the part can be unfolded flat, it should normally be modelled as a sheet-metal part.

## SolidWorks workflow

Use the Sheet Metal environment from the start. The model should produce:

- a flat pattern for a drawing or DXF export;
- bend lines and an accurate bend allowance;
- visible corner relief, flange and bend-interference checks.

Do not create the unfolded shape manually. Set sheet thickness, bend radius and K-factor to match the material and intended tooling. Standard values should be stored in a shared gauge table when they have been confirmed.

## Before release

- Confirm that the available tooling can form every bend.
- Check flange lengths, bend sequence, corner reliefs and tool access.
- Confirm the material, thickness, bend radius and K-factor with the manufacturer.
- Export the flat pattern at 1:1 scale with bend lines clearly identified.
- Nest externally cut parts onto standard sheets where practical.

The FTX7 reference used 2500 × 1250 mm sheet in 1.5 mm and 3 mm thicknesses. See [Materials & Stock](../workshop-reference/materials-stock.md) before standardising a new design.
