# Penteract
Open-source Core-xy motion platform mainly for "large" print volume desktop 3D printer

---
# Introduction
The Penteract is a open-source Core-xy motion platform with a ridgid main chassis using 3030 aluminum extrusions and light moving compoents constuted by 1515 aluminum extrusions.

Due to the design being motion platform, components like the motherboard, LED lights, HEPA filters, etc. are for the individual builder to determine. in addtion, the "Penteract calculator" will output the length of components to accommodate various sizes requrents.

---
# Community: [Discord](https://discord.gg/vaqBpfTSvp)
- The announcement will explain alot of the incompeletness of this project
- Desginer will be there on the weekends answering questions

---
# DISCLAIMER: Not for the faint of heart
- This project is in development
- Current documentations are barebones to put it nicely
- The their is a high posiblity that the firmware will not be  
- The rate of deveolpent and updates will be uncertain until the first quarter of 2022 (refer to the announcement in the Discord sarver)
- The cost of building will prabably be higher then you think
- The allowable tolrace of the printed parts are tight

---
# Recomended Print Settings
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
# Notes on Modificaiton
## [Penteract Calculator (INCOMPLEAT)](https://docs.google.com/spreadsheets/d/1V_LHIspbQpN_TUXLFGDAbgbeAjzPKB1Uei0glfI2XhU/edit?usp=sharing)
If one wants to have difftent print volume
- Recomended X-axis "Print Voulume" : 250mm ≤ (x axis "Print Voulume) ≤ 450mm
- Havy modfifiaction will be needed to the Z axis if one wants to go with larger print volume then standard.

### How to use the calculator (Rough Quality):
[![](http://img.youtube.com/vi/7c40CwL1CLM/0.jpg)](http://www.youtube.com/watch?v=7c40CwL1CLM "How to Use the Calculator")

---
# Bill of Material Recommendations (INCOMPLEAT)
This is not a comprehensive list of Materials but a list of recomendations

## Bolts: the M3 Socket head bolt length and quantity update will be uncertain until the first quarter of 2022
Size | Length | Type | Quantity
--- | --- | --- | --- |
M6 | 15mm | Button Head | 62
M5 | 45mm | Hex Head | 2
M3 | "n"mm | Socket Head | "n" 
M2 | 12mm | Socket Head | 4

## Nuts
Size | Type | Quantity
--- | --- | --- |
M6 | for 30x30mm Extrusions | 62
M3 | for 30x30mm Extrusions | (total # of mounting holes in the MGN12H rails for the 30x30mm Extrusion) 
M3 | for 15x15mm Extrusion | (Packet of more then 50 is recomended)
M3 | Standard Hex | 2
M3 | Standard Hex | (Packet of more then 50 is recomended)
M2 | Standard Hex | 4

## Electrical Components
Components | Recommended Product | Spcifications | Quantity
--- | --- | --- | --- |
Hotend | E3D V6 | 1.75mm / 24V(Recommended) / Direct Drive | 1
Endstop | Omron SS-01-E | --- | 2
Z-probe | BL touch v3 | --- | 1
Stepper Motor (XY Axis) | --- | NEMA 17 / 24V(Recommended) | 2
Stepper Motor (Extruder) | (the motor will come with the Orbiter v1.5) | --- | 1
Stepper Motor (Z Axis) | E3D LEADSCREW MOTOR WITH POM NUT (dos not nessasarly have to be this one. ONLY for build for the CAD file spcifications) | NEMA 17 / Body Length: < 30mm / Integrated Lead Screw Length: (in Calculator) | 2

## Mechanical Components
Components | Spcifications | Misumi Search Tearm | Quantity
--- | --- | --- | --- |
Extruder | Orbiter v1.5 | --- | 1
[Smooth Idler (Highly spsific, using this link is hightly recommended)](https://e3d-online.com/products/gates-powergrip®-2gt-idlers?_pos=1&_sid=273afe3ac&_ss=r) | GT2® / OD: 12mm / for 6mm Belt / 5mm | --- | 4
[Toothed Idler (Highly spsific, using this link is hightly recommended)](https://e3d-online.com/products/gates-powergrip®-2gt-idlers?_pos=1&_sid=273afe3ac&_ss=r) | GT2® / 20T / for 6mm Belt / 5mm | --- | 6
Drive Pulley | GT2® / 20T / for 6mm Belt / 5mm | --- | 6
Timming Belt | GT2® / Width: 6mm Belt / --- | Lengths: (in Calculator) | 2
Liner Rails | MGN12H / Lengths: (in Calculator or CAD) | --- | 3
Liner Rods | Diameter: 12mm / Heat treated steel / crome coated | PSFU12(Recommendation) | 2
Liner Rods | LM12LUU | SLMUW12(Recommendation) | 2
Idler Pins | Diameter: 5mm / Length: 30mm | --- | 10

## Frame: The 3D printed parts of the Penteract was spcifcly designed to use Misumi aluminum 3030 extrusions (not the case for 1515 extrusions)
Components | Spcifications | Misumi Search Tearm | Quantity
--- | --- | --- | --- |
30x30  Aluminum Extrusions | Lengths: (in Calculator or CAD) | "GFS6-3030"(Standard) or "GNFS6-3030"(Economy) | (in Calculator or CAD)
30x30 Aluminum Extrusions for liner rail Mouting | Lengths: (in Calculator or CAD) | HFSP6-3030 | 2
15x15 Aluminum Extrusion | Lengths: (in Calculator or CAD) | HFS3-1515 | (in Calculator or CAD)
