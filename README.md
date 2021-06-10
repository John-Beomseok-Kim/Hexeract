# Hexeract
Open-source Core-XY motion platform mainly for "large" print volume desktop 3D printer
![PENTERACT__Motion_ _Extrusion Platform v81](https://user-images.githubusercontent.com/76419272/110213799-ed12af00-7ee4-11eb-9770-255e31e7c31a.png)

---
# Introduction
The Penteract is an open-source Core-XY motion platform with a rigid main chassis using 3030 aluminum extrusions and moving components constructed by 1515 aluminum extrusions.

The design is a motion platform, components like; motherboard, LED lights, HEPA filters, and more are for the individual builder to determine. Also, the "Penteract calculator" will output the length of components to accommodate various size requirements.

---
# DISCLAIMER: Not for the faint of heart
- The cost of building will probably be higher than you think
- The allowable tolerance of the printed parts are tight
## The rate of development and updates will be uncertain until the first quarter of 2022 (refer to the announcement in the Discord server)
- This project is in development
- The current "Bill of Materials" and "Assembly Guide" are barebones
- The "Calculator" is incomplete

---
# Community: [Discord](https://discord.gg/vaqBpfTSvp)
- The announcement will explain a lot of the incompleteness of this project
- Designer will be there on the weekends answering questions

---
# Recomended Print Settings for 3D Printed Parts
- **Filament Material:** PETG, ABS, ASA
- **Layer Hight:** 0.2mm
- **Extrusion Width:** 0.4mm
- **Infill Percentage:** 20%
- **Infill Pattern:** "Tri-Haxagon"[Cura] / "Star"[PrusaSlicer]
- **Supports:** NO
- **Ironing Pattern:** Zig Zag[Cura]
- **Brim Line (Count / Width):** 15 Lines / 6mm
- **Print Wall (Count / Thickness):** 4 Lines / 1.6mm
- **Top & Bottom Layer (Count / Thickness):** 8 Layers / 1.6mm

---
# Penteract Calculator (In Working Progress)
If one wants to have a different print volume
- Recommended X-axis "Print Volume" : 250mm ≤ (x-axis "Print Volume") ≤ 450mm
- Significant modification will be necessary to the Z-axis if one wants to go with a larger print volume than standard.

## How to use the calculator (In Working Progress):
[![](http://img.youtube.com/vi/7c40CwL1CL%M%/0.jpg)](http://www.youtube.com/watch?v=7c40CwL1CL%M% "How to Use the Calculator")

---
# [CAD File Link](https://a360.co/33fj55M)

---
# Bill of Material Recommendations
*not a comprehensive list of materials but a list of recommendations

## Bolts: the M3 Socket head bolt length and quantity update will be uncertain until the first quarter of 2022
Size | Length | Type | Quantity
--- | --- | --- | --- |
M8 | 15mm | Black Oxide Steel Finish / Button Head | 8
M8 | 25mm | Black Oxide Steel Finish / Button Head | 16
M8 | 45mm | Black Oxide Steel Finish / Socket Head | 4
M6 | 15mm | Button Head | 62
M5 | 45mm | Hex Head | 2
M3 | "n"mm | Socket Head | "n" 
M2 | 12mm | Socket Head | 4

## Nuts
Size | Type | Quantity
--- | --- | --- |
M6 | for 30x30mm Extrusions | 62
M3 | for 30x30mm Extrusions | (total # of mounting holes in the MGN12H rails for the 30x30mm Extrusion) 
M3 | for 15x15mm Extrusion | (Packet of more than 50 recommended)
M3 | Standard Hex | 2
M3 | Standard Hex | (Packet of more than 50 recommended)
M3 | Length: ≥7mm / Hex | 4
M2 | Standard Hex | 4

## Washers
Size | Type | Quantity
--- | --- | --- |
M3 | Stainless Steel / Standard size | 20(Recommended)

## Electrical Components: If given the chioce, 24v is hightly recommended
Components | Recommended Product | Spcifications | Quantity
--- | --- | --- | --- |
Hotend | E3D V6 | 1.75mm / Direct Drive | 1
Endstop | Omron SS-01-E | --- | 2
Z-probe | BL touch v3 | --- | 1
Part cooling fan | --- | 5015 Blower fan | 1
Stepper Motor (XY Axis) | --- | NEMA 17 | 2
Stepper Motor (Extruder) | (the motor will come with the Orbiter v1.5) | --- | 1
Stepper Motor (Z-Axis) | E3D LEADSCREW MOTOR WITH POM NUT (dos do not have to be this one. ONLY for CAD file specification build) | NEMA 17 / Body Length: < 30mm / Integrated Lead Screw Length: (in the calculator) | 2
Print Bed | E3D High-Temperature Heated Bed | --- | 1

## Notes on Wiring
**DISCLAIMER: Recommendations from a nonexpert in electronics. These recommendations will not be responsible if accidents happen**
- Mains voltage could kill a person so, please be careful when wiring mains wires
- Crimp electrical connections where possible.
- For mains wires, 12 AWG copper wire is recommended
- For 24v wires, 22 AWG fine strand wire is recommended

## Mechanical Components
Components | Spcifications | Misumi Search Term | Quantity
--- | --- | --- | --- |
Extruder | Orbiter v1.5 | --- | 1
[Smooth Idler (Highly spsific, using this link is hightly recommended)](https://e3d-online.com/products/gates-powergrip®-2gt-idlers?_pos=1&_sid=273afe3ac&_ss=r) | GT2® / OD: 12mm / for 6mm Belt / 5mm | --- | 4
[Toothed Idler (Highly spsific, using this link is hightly recommended)](https://e3d-online.com/products/gates-powergrip®-2gt-idlers?_pos=1&_sid=273afe3ac&_ss=r) | GT2® / 20T / for 6mm Belt / 5mm | --- | 6
Drive Pulley | GT2® / 20T / for 6mm Belt / 5mm | --- | 6
Timming Belt | GT2® / Width: 6mm Belt / Length: (in Calculator) | --- | 2
Liner Rail | MGN12H / Lengths: (in Calculator or CAD) | --- | 3
Liner Rod | Diameter: 12mm / Heat treated steel / crome coated | PSFU12(Recommendation) | 2
Liner Bearing | LM12LUU | SLMUW12(Recommendation) | 2
XY Motor Mount Bearing | 625 Bearing  | --- | 2
Idler Pin | Diameter: 5mm / Length: 30mm | --- | 10
XY Motor Mount Pin | Diameter: 3mm / Length: 15mm | --- | 2
Belt Tensioner Pin | Diameter: 3mm / Length: 35mm | --- | 4
Print Head Prin | Diameter: 3mm / Length: 47mm | --- | 2
End Stop Tigger Prin | Diameter: 3mm / Length: 10mm | --- | 2
End Stop Mount Prin | Diameter: 3mm / Length: 12mm | --- | 2
Bed Bracket Collar | OD: 6mm / ID: 3mm / Length: 12mm | KNCLSS3-6-12(Recommendation) | 4
Bed Spring | OD: 6mm / ID: >3mm / Length: 15mm | SWF6-15(Similar spec spring will be hard to find)| 4

## Frame: The 3D printed parts of the Penteract are spcifcly designed to use Misumi aluminum 3030 extrusions (not the case for 1515 extrusions)
Components | Spcifications | Misumi Search Term | Quantity
--- | --- | --- | --- |
3030 Aluminum Extrusions | Lengths: (in Calculator or CAD) | "GFS6-3030"(Standard) or "GNFS6-3030"(Economy) (additonal machining will be requred, Refer to the CAD) | (in Calculator or CAD)
3030 Aluminum Extrusion for liner rail Mouting | Lengths: (in Calculator or CAD) | HFSP6-3030 | 2
1515 Aluminum Extrusion | Lengths: (in Calculator or CAD) | HFS3-1515 | (in Calculator or CAD)

# Assembly Guide
- Insert the **45mm hex head M5 screw** FIRST in the "P_Belt_Tensioner" during assembly.
- All the Brackets that attach to the 3030 aluminum extrusions will use **15mm button head M6 screws** to attach
- All the Brackets that attach to the 1515 aluminum extrusions will use **8mm socket head M3 screws** to attach
- A rubber, wooden, or plastic mallet/hammer could be necessary to tap in the press-fit components

## Recommended Tools: Quality will matter to an extent
- 2.5mm ball-end hex screwdriver
- 4 hex Allen wrench with ball-end
- 5 and 6 mm hex Allen wrench
- Nipper
- Rubber mallet
- Ferrule Crimpers
- Engineer PA-09
- Engineer PA-05
- PTFE based synthetic grease

---
# Cradits and Inspration
## Main Design Architacture inspration:
- [Hypercube Evolution](https://www.thingiverse.com/thing:2254103)
- [RailCore II](https://railcore.org)
- [Voron 1](https://vorondesign.com/voron1.8)
- [BLV mgn Cube](https://www.blvprojects.com/blv-mgn-cube-3d-printer)
## Elements of 3D Printed Parts Design:
- [Prusa i3 Bear Upgrade](https://github.com/gregsaun/prusa_i3_bear_upgrade)
## This design uses:
- E3D V6
- BL touch v3
- Orbiter v1.5
## Thank You
- All the members of the Penteract Discord server for supporting the project
- Members in "[Hypercube Evolution Pro modified](https://www.facebook.com/groups/hevopro)" Facebook group where this project started
- Members of the "Annex-Engineering" Discord server
