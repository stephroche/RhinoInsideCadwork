## User Attributes

User attributes can be created for the cadwork elements. These can be added as input parameters. 

![Backup Text](../img/cadwork_attributes.jpg "Axis"){: style="width:600px"}

Input           | comment 
----------------|:---------
Name | Name
Group | Group
Subgroup | Subgroup
Comment | Comment
Edvcode | EDV - Code
User1-99 (Keys) | User Attributes <br>**Name of the attribute must exist in cadwork**.<br> To create the attribute via Grasshopper the **prefix cw_** must be prefixed.
User1-99 (Values) | String 


Output           | comment 
-----------------|:---------
OutputStdAttr | Return the create cadwork attributes


## Standard Attributes

![Backup Text](../img/standard_attributes.jpg "Axis"){: style="width:600px"}

Input           | comment 
-----------------|:---------
Material | Material name
Color | Color number
NrProdList | Production List Number
NrTimberList | BOM number
NrAssemlbyList | Assembly List Number
RoundingValueLength [mm] [rounding value length
RoundingValueWidth [mm] [Rounding value width
RoundingValueHeight [mm] [rounding value height
ListOverwidth | Width raw [mm]
ListOverheight [height raw] [mm
ListOverlength | Length raw [mm]
ProcessingType [output type
ProcessingQuality [processing quality
ProcessingAddData [additional settings
RoughOverheightPos [mm] [Positive height axis
RoughOverheightNeg [negative height axis] [mm
RoughOverwidthPos | Positive width axis [mm]
RoughOverwidthNeg | Negative width axis [mm]
BIMBuilding | Building
BIMStorey [floor 
BimStoreyEleveationInMM | Floor Height in [mm]
IfcElementType | IfcType (e.g. IfcMember)

Output           | comment 
-----------------|:---------
OutputCwAttr | Return the created cadwork attributes

## Filter by Attributes

Brep's can be filtered by defined keys/values via this component. 

![Backup Text](../img/filterbyattribute.jpg "Axis")

Input           | comment 
-----------------|:---------
InputBrep | Brep's
CwAttr | Cadwork-Attribut
StdAttr | Standard-Attribut
FilterKeys | Filter Keys <br> Note spelling <br> :white_check_mark: **CW$_foo_bar**
FilterValues | Value to be filtered by

Output           | comment 
-----------------|:---------
OutputBrep | Return of the filtered brep

## Keys to Values
Retrieve attribute values according to given keys.

Filter by default attributes
![Backup Text](../img/keystovalues.jpg "Axis")

Filter by user attributes
![Backup Text](../img/cwkeystoval.jpg "Axis")

Input           | comment 
-----------------|:---------
CwAttr | cadwork Attributes
StdAttr | Standard Attributes
Keys | Key to filter by <br> Note prefix!<br> :white_check_mark: **StdAttr CW$_** <br> :white_check_mark: **CwAttr cw_**

Output           | comment 
-----------------|:---------
OutputBrep | Return of the filtered brep

## Working with Standard Attributes 

### Output Standard-Attribute
Name           | Return value 
-----------------|:---------
CW$_material | String
CW$_color | Integer
CW$_number_production_list | Integer
CW$_number_timber_list | Integer
CW$_number_assembly_list | Integer
CW$_rounding_value_width | Real
CW$_rounding_value_height | Real
CW$_rounding_value_length | Real
CW$_list_overwidth | Real
CW$_list_overheight | Real
CW$_list_overlength | Real
CW$_processing_type | Integer
CW$_processing_quality | Integer
CW$_processing_add_data | Integer
CW$_xsection_type | Integer
CW$_rough_overheight_pos | Real
CW$_rough_overheight_neg | Real
CW$_rough_overwidth_pos | Real
CW$_rough_overwidth_neg | Real
CW$_BIMBuilding | String
CW$_BIMStorey | String 
CW$_IfcElementType | String



### ProcessingType
Name           | Number (Integer) 
-----------------|:---------
No output type | 0
Rafter | 1
Purlin | 2
Shifter | 3
block plank | 4
Stem | 6
Truss | 7
hip/valley rafter | 11
User 1 | 20
User 2 | 21
User 3 | 22
User 4 | 23
User 5 | 24
Stage | 30
Plate 1 | 120
Plate 2 | 121
Plate 3 | 122
Plate 4 | 123
Plate 5 | 124


### ProcessingQuality
Name           | Number (Integer) 
-----------------|:---------
None | 0
Cerve | 1
Hearterve | 2
Leaf | 4
ridge leaf | 8
Tanner butt | 16
Offset | 32
Bore | 64
Profile | 128
Slot | 256
Eave formwork | 512
Hook blade | 1024
Face groove | 2048
SS groove inside | 4096
SS groove outside | 8192
Witch cut | 16348
PlaningTotal | 32768

### ProcessingAddData
Name           | Number (Integer) 
-----------------|:---------
None | 0
Output ESZ single | 16393
Output ESZ wall | 16396
Reference Container | 16408
Multifunction bridge | 16424
Log macro in BVN | 16904
Processing in single component | 16520
Ignore for VBA | 18440
All | 19133

### XSectionType

Name           | Number (Integer) | comment
-----------------|:---------|:---------
Square cross section. | 1 | 
Rectangular cross section | 2 | 
Round cross section | 3 | 
Plate Rectangle | 17 | 

