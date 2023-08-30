# pcb-fabrication-UoE
Notes and Instructions for PCB fabrication using UoE In house fabrication services and KiCAD

## Design Constraints

| Feature | Min | Max | Reccomended |
|---      |---  |---  |---          |
|via drill| 0.8 |     |   1         |
| via size|  1  |     |  1.4        | 


## Fabrication Outputs

### Drill Files
- Ensure that Drill/Place origin is set to top left hand corner of PCB template.
- Ensure that settings match image below.
![image](https://github.com/ImogenWren/pcb-fabrication-UoE/assets/97303986/864be83e-9357-46bc-90ec-f412e207b371)


### Copper Layers & Silkscreen
_Copper layers and silkscreen are processed as individual files in PDF format._

Files Must:
-  Contain a single layer only
-  Be the same size as the PCB Template! - No whitespace
-  PDF format
-  Black and white only

Copper Layer files are used to print etch mask directly to PCB template board before etching. <br>

Silkscreen printed directly to etched PCB.

#### Exporting Files

_KiCAD cannot export to PDF directly, must convert SVG to PDF externally_

##### Exporting SVG Per Layer
![image](https://github.com/ImogenWren/pcb-fabrication-UoE/assets/97303986/dfc46394-ea5d-4522-83b6-f8801ebcc70d)

Rename files as they are exported.


