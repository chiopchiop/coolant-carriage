# 🚟coolant-carriage
A computer numerical control (CNC) machine is used to cut and shape materials to form prototypes. A coolant is often used to act as a lubricant to aid a CNC machine to easily cut materials such as metals, fibreglass, high-density plastics, etc. The majority of the workload in the lab involves machining aluminium, which is work-hardening material. This necessitates the use of a coolant to promptly remove generated chips from the work area and prevent them from becoming caught in the endmill. If chips become trapped, they can mar the workpiece, alter the required cutting force, and induce chattering. The current CNC machine in the lab uses a Minimum Quantity Lubrication (MQL) system. In such systems, the amount of coolant in the airstream is set by adjusting the pressure of the coolant takeup tube. In larger industrial systems, a metering valve is used. However, this is performed using height adjustment with a manual siphon system i.e. A tube immersed in a container of 99% Isopropyl Alcohol (IPA) is hand raised to different heights to allow the coolant to flow down to the coolant jet in the CNC machine at different pressures (Figure 2-1). Feedback from CNC machine operators indicates that the manual siphon system is both inefficient and tiring, disrupting workflow and causing user fatigue. In this project, a coolant carriage will be designed to hold the container and is free to slide smoothly vertically along an aluminium V profile. 

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/43da6db5-81fe-4188-a36a-bb93a10dd1d2)' width='500'>\
*Figure 1. Full coolant carriage set up*

### Table of contents
[Proposed idea](https://github.com/chiopchiop/coolant-carriage#proposed-idea-v-slot-gantry-plate-with-carriage-on-three-v-slot-aluminium-profiles)\
[Bill of materials/Assembly](https://github.com/chiopchiop/coolant-carriage#bill-of-materials-bom)
[How to use](https://github.com/chiopchiop/coolant-carriage#how-to-use)

## Proposed idea: V slot gantry plate with carriage on three V slot aluminium profiles

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/4e79385d-3194-4227-a27d-77fc4e4067c3)' width='500'>\
*Figure 2. Initial setup vs proposed setup and the components to be designed*

### Bill of Materials (BOM)
List of components for the carriage to be 3D modelled with Fusion 360:
- V slot gantry plate to slide along the aluminium profile (Plate)
- Ratchet and pawl to move/stop carriage along the V profile (Ratchet) (Pawl)
- Carriage to hold the coolant bottle (Carriage)
- Bracket to hold the three aluminium profiles together (Bracket)
- Caps to protect against the sharp edges of the aluminium profiles (Caps)
- Bottle cap that is able to hold the siphon (Bottle cap)

See .stl file for 3D printing files/instructions

**Consolidated materials**
| Item # | Components  | Length | Qty |
| --- | --- | --- | ---|
|1 |3D printed plate |-    |1 |
|2 |3D printed pawl  |- |1 |
|3 |3D printed ratchet tiles      |-    |2 |
|4 |3D printed carriage (backing)  |-  |1 |
|5 |3D printed carriage (clamp)  |-    |1 |
|6 |3D printed bracket      |-    |1 |
|7 |3D printed cap 40x20 |-    |1 |
|8 |3D printed cap 20x20 |-    |2 |
|9 |3D printed bottle cap   |- |1 |
|10 |V slot aluminium profile 40x20 |500mm   |1 |
|11 |V slot aluminium profile 20x20 |203mm/8inch |2 |
|12 |M5x6x7 heat insert  |-    |2 |
|13 |M5 screw |6mm    |2 |
|14 |M5 screw       |35mm |6 |
|15 |M5 screw      |8mm    |6 |
|16 |M5 roll-in nut      |-    |2 |
|17 |M5 spacer      |8mm    |2 |
|18 |M5 washer      |-    |4 |
|19 |M5 nut      |-    |4 |
|20 |M5 eccentric screw      |8mm    |2 |
|21 |M3x4.6x5.7 heat insert      |-    |2 |
|22 |M3 flathead screw |6mm    |8 |
|23 |M3 screw |6mm    |2 |
|24 |M3 screw       |8mm |4 |
|25 |M3 roll-in nut       |- |8 |
|26 |M3 Rubber feet |-    |4 |
|27 |M3 roll-in nut |-    |4 |


**Assembling Plate x 1**
| Item # | Components  | Length | Qty |
| --- | --- | --- | ---|
|1 |M5x6x7 heat insert |-    |2 |
|2 |M5 screw       |35mm |4 |
|3 |M5 spacer      |8mm    |2 |
|4 |M5 washer      |-    |4 |
|5 |M5 nut      |-    |4 |
|6 |M5 eccentric screw      |8mm    |2 |
|7 |M3x4.6x5.7 heat insert      |-    |2 |

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/1afaba48-f15b-4992-bc3d-8327ed2be92e' alt= 'Assembly diagram_plate' width='250'>\
*Figure 3. Position of heat inserts on the plate. Ignore the workmanship:grin:*

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/0ef37caa-1009-48d8-aa69-8c05a245089d' alt= 'Assembly diagram_plate2' width='400'>\
*Figure 4. Assembling the wheels of the plate. Wheels on the left side will be fixed, while wheels on the right can be adusted with the eccentric nut*

**Assembling Ratchet Tiles x 2**
| Item # | Components  | Length | Qty |
| --- | --- | --- | ---|
|1 |M3 flathead screw |6mm    |8 |
|2 |M3 roll-in nut       |- |8 |

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/2d9423dc-9e5d-44b7-ad76-08fde8b52688' alt= 'Assembly diagram_ratchet' width='400'>\
*Figure 5. Assembling the ratchet tiles to the aluminium profile(40x20)*

**Assembling Pawl/Hinge x 1**
| Item # | Components  | Length | Qty |
| --- | --- | --- | ---|
|1 |M3 screw |6mm    |2 |

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/b4ef17ff-71bd-4026-a0c6-9719596a8144' alt= 'Assembly diagram_pawl' width='400'>\
*Figure 6. Assembling the pawl to the plate*

**Assembling Carriage x 1**
| Item # | Components  | Length | Qty |
| --- | --- | --- | ---|
|1 |M5 screw |6mm    |2 |

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/0ba6ba58-949d-48c7-bd46-23aabc61c14b' alt= 'Assembly diagram_carriage' width='350'>\
*Figure 7. Assembling the carriage to the plate*

**Assembling Bracket x 1**
| Item # | Components  | Length | Qty |
| --- | --- | --- | ---|
|1 |V slot aluminium profile 40x20 |-    |1 |
|2 |V slot aluminium profile 20x20 |203mm/8inch |2 |
|3 |M5 screw      |8mm    |6 |
|4 |M5 screw      |35mm    |2 |
|5 |M5 roll-in nut      |-    |2 |

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/2346035d-ade7-4a7a-ae84-3c0681184270' alt= 'Assembly diagram_bracket' width='500'>\
*Figure 8. Connecting the 3 aluminium profiles to the bracket with M5 screws*

**Assembling Rubber Feet**
| Item # | Components  | Length | Qty |
| --- | --- | --- | ---|
|1 |M3 Rubber feet |-    |4 |
|2 |M3 screw       |8mm |4 |
|3 |M3 roll-in nut |-    |4 |

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/8b479370-1e4e-47cc-87d2-b680bd4e509b' alt= 'Assembly diagram_rubberfeet' width='300'>\
*Figure 8. Postions of the rubber feet under the aluminium profiles, using M3 screws to secure them*

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/ba821ba1-ddea-4a35-b5b6-6aeabc233aec' alt= 'Assembly diagram_caps' width='500'>\
*Figure 8. Attach caps to the edges of the aluminium profile*

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/d3697def-279d-459c-9040-4f07ae726336' alt= 'Assembly diagram_finalproduct' width='500'>\
*Figure 8. Completed coolant carriage*

### How to use
https://youtube.com/shorts/JxCeHPnCB4s

<a href="http://www.youtube.com/watch?feature=player_embedded&v=JxCeHPnCB4s
" target="_blank"><img src="http://img.youtube.com/vi/JxCeHPnCB4s/0.jpg" 
alt="how to" width="500" /></a>

That concludes this project 🎺!
