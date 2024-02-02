# 🚟coolant-carriage
A computer numerical control (CNC) machine is used to cut and shape materials to form prototypes. A coolant is often used to act as a lubricant to aid a CNC machine to easily cut materials such as metals, fibreglass, high-density plastics, etc. The majority of the workload in the lab involves machining aluminium, which is work-hardening material. This necessitates the use of a coolant to promptly remove generated chips from the work area and prevent them from becoming caught in the endmill. If chips become trapped, they can mar the workpiece, alter the required cutting force, and induce chattering. The current CNC machine in the lab uses a Minimum Quantity Lubrication (MQL) system. In such systems, the amount of coolant in the airstream is set by adjusting the pressure of the coolant takeup tube. In larger industrial systems, a metering valve is used. However, this is performed using height adjustment with a manual siphon system i.e. A tube immersed in a container of 99% Isopropyl Alcohol (IPA) is hand raised to different heights to allow the coolant to flow down to the coolant jet in the CNC machine at different pressures (Figure 2-1). Feedback from CNC machine operators indicates that the manual siphon system is both inefficient and tiring, disrupting workflow and causing user fatigue. In this project, a coolant carriage will be designed to hold the container and is free to slide smoothly vertically along an aluminium V profile. 

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/ffeaff79-aea1-4d01-9535-3f7083be50a8' alt= 'full coolant carriage set up' width='500'>\
*Figure 1. Full coolant carriage set up*

### Table of contents
[Proposed idea](https://github.com/chiopchiop/coolant-carriage#proposed-idea-v-slot-gantry-plate-with-carriage-on-three-v-slot-aluminium-profiles)\
[Bill of materials/Assembly](https://github.com/chiopchiop/coolant-carriage#bill-of-materials-bom)\
[How to use](https://github.com/chiopchiop/coolant-carriage#how-to-use)

## Proposed idea: V slot gantry plate with carriage on three V slot aluminium profiles
<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/596c94ff-5eb3-4a2a-b913-0abda3ff9af5' alt= 'Proposed idea' width='500'>\
*Figure 2. Initial setup vs proposed setup and the components to be designed*

## Bill of Materials (BOM)
List of components for the carriage to be 3D modelled with Fusion 360:
- V slot gantry plate to slide along the aluminium profile (Plate)
- Ratchet and pawl to move/stop carriage along the V profile (Ratchet) (Pawl)
- Carriage to hold the coolant bottle (Carriage)
- Bracket to hold the three aluminium profiles together (Bracket)
- Caps to protect against the sharp edges of the aluminium profiles (Caps)
- Bottle cap that is able to hold the siphon (Bottle cap)

STL files, quantity, and orientation of the part are in the the STL files folder

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

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/5b265070-e9e2-403f-9ab4-1dc96963aafe' width='250'>\
*Figure 3. Position of heat inserts on the plate. Ignore the workmanship :grin:*

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/267ee97f-0ec3-48aa-bd41-bda63bfb1af7' alt= 'Assembly diagram_plate2' width='400'>\
*Figure 4. Assembling the wheels of the plate. Wheels on the left side will be fixed, while wheels on the right can be adusted with the eccentric nut*

**Assembling Ratchet Tiles x 2**
| Item # | Components  | Length | Qty |
| --- | --- | --- | ---|
|1 |M3 flathead screw |6mm    |8 |
|2 |M3 roll-in nut       |- |8 |

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/ce7f213b-1684-4088-862f-9b5e323a8bd1' width='400'>\
*Figure 5. Assembling the ratchet tiles to the aluminium profile(40x20)*

**Assembling Pawl/Hinge x 1**
| Item # | Components  | Length | Qty |
| --- | --- | --- | ---|
|1 |M3 screw |6mm    |2 |

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/75e95fbf-e1e2-4881-99c2-9faf67355806' width='400'>\
*Figure 6. Assembling the pawl to the plate*

**Assembling Carriage x 1**
| Item # | Components  | Length | Qty |
| --- | --- | --- | ---|
|1 |M5 screw |6mm    |2 |

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/d34e61b3-824b-4d93-9165-af04c62c66bb' width='350'>\
*Figure 7. Assembling the carriage to the plate*

**Assembling Bracket x 1**
| Item # | Components  | Length | Qty |
| --- | --- | --- | ---|
|1 |V slot aluminium profile 40x20 |-    |1 |
|2 |V slot aluminium profile 20x20 |203mm/8inch |2 |
|3 |M5 screw      |8mm    |6 |
|4 |M5 screw      |35mm    |2 |
|5 |M5 roll-in nut      |-    |2 |

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/6c990fac-a1b1-46f0-b311-d04b46aae125' width='500'>\
*Figure 8. Connecting the 3 aluminium profiles to the bracket with M5 screws*

**Assembling Rubber Feet**
| Item # | Components  | Length | Qty |
| --- | --- | --- | ---|
|1 |M3 Rubber feet |-    |4 |
|2 |M3 screw       |8mm |4 |
|3 |M3 roll-in nut |-    |4 |

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/f314fdf3-b302-40c6-bad5-4b78f9e0a9b8' width='300'>\
*Figure 8. Postions of the rubber feet under the aluminium profiles, using M3 screws to secure them*

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/da3d0276-4109-4095-93dc-98fed58d0209' width='500'>\
*Figure 8. Attach caps to the edges of the aluminium profile*

<img src='https://github.com/chiopchiop/coolant-carriage/assets/135982821/a7a236a3-2dda-4b4a-a06c-6fb191468d54' alt= 'Assembly diagram_finalproduct' width='500'>\
*Figure 8. Completed coolant carriage*

## How to use
https://youtube.com/shorts/JxCeHPnCB4s

<a href="http://www.youtube.com/watch?feature=player_embedded&v=JxCeHPnCB4s
" target="_blank"><img src="http://img.youtube.com/vi/JxCeHPnCB4s/0.jpg" 
alt="how to" width="500" /></a>

That concludes this project 🎺!
Special thanks to the people at Liang Research Group for the guidance and facilities! (https://liangresearch.com/)
