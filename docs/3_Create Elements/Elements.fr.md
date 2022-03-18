Les composants suivants permettent de générer des éléments cadwork. Les éléments sont représentés comme des éléments verrouillés dans cadwork. Dès que les éléments sont "cuits", le verrouillage est levé. La cuisson s'effectue via le menu contextuel.

![Backup Text](../img/context.jpg "context menü"){: style="width:300px"}

**Bake all to cadwork** libère tous les éléments créés avec Grasshopper (le verrouillage des éléments est levé). 

## Beam

Le composant **Beam** génère une barre dans cadwork. 
En plus de l'entrée géométrique obligatoire, les possibilités **Axis, CwAttr, StdAttr** sont disponibles en option. 

![Backup Text](../img/beam.png "Beam"){: style="width:600px"}

Input           | comment 
----------------|:---------
Geom | Brep closed
Axis | Système d'axes [optional]
CwAttr | Userattributes [optional]
StdAttr | Standardattributes [optional]


Output           | comment 
-----------------|:---------
None | L'élément est généré dans cadwork

Avec un clic droit sur l'icône, on peut sélectionner dans le menu contextuel l'option **Cadwork Preview, Bake to Cadwork, Bake all to Cadwork**. Cela permet de lire les axes des composants. 
![Backup Text](../img/beam_bake.png "Beam"){: style="width:600px"}

## Panel

Le composant **Panel** génère un panneau dans cadwork.
![Backup Text](../img/panel.png "Panel"){: style="width:600px"}

Input           | comment 
----------------|:---------
Geom | Brep closed
Axis | Système d'axes [optional]
CwAttr | Userattributes [optional]
StdAttr | Standardattributes [optional]


Output           | comment 
-----------------|:---------
None | L'élément est généré dans cadwork

## Auxiliary Element

Le composant **AuxVol** génère un volume auxiliaire dans cadwork.
![Backup Text](../img/auxi.png "Panel"){: style="width:600px"}

Input           | comment 
----------------|:---------
Geom | Brep closed
CwAttr | Userattributes [optional]
StdAttr | Standardattributes [optional]


Output           | comment 
-----------------|:---------
None | L'élément est généré dans cadwork

## Drilling

Le composant **Drilling** génère un boulon dans cadwork. Le composant nécessite comme entrée un **point 1, point 2, diamètre**. La **surépaisseur de perçage ainsi que les attributs** peuvent être ajoutés en option. 

![Backup Text](../img/drill.png "Drilling"){: style="width:600px"}

![Backup Text](../img/drilling.png "Drilling"){: style="width:600px"}

Input           | comment 
----------------|:---------
Point_1 | Point de départ
Point_2 | Point final
Diameter | Diamètre [mm]
Supplement | Apport Alésage [mm]
CwAttr | Standardattributes
StdAttr | Standardattributes


Output           | comment 
-----------------|:---------
None | L'élément est généré dans cadwork

## Bauteilachsen

Les axes locaux des composants sont définis par le composant **Axis**. 
Un vecteur X ainsi qu'un vecteur Z sont indiqués. 

![Backup Text](../img/axis1.png "Axis"){: style="width:600px"}

Input           | comment 
----------------|:---------
VectorXLocal | {x, y, z}
VectorYLocal | {x, y, z}


Output           | comment 
-----------------|:---------
OutputAxis | Restitution du niveau cadwork

## Create Surface

Le composant **AuxVol** génère un volume auxiliaire dans cadwork.
![Backup Text](../img/createSurface.jpg "Surface"){: style="width:600px"}

Input           | comment 
----------------|:---------
Geom | Surface
CwAttr | Userattributes [optional]
StdAttr | Standardattributes [optional]


Output           | comment 
-----------------|:---------
None | L'élément est généré dans cadwork

## Create Line

Le composant **AuxVol** génère un volume auxiliaire dans cadwork.
![Backup Text](../img/createLine.jpg "Surface"){: style="width:600px"}

Input           | comment 
----------------|:---------
Geom | Line
CwAttr | Userattributes [optional]
StdAttr | Standardattributes [optional]


Output           | comment 
-----------------|:---------
None | L'élément est généré dans cadwork

## Create Node

Le composant **AuxVol** génère un volume auxiliaire dans cadwork.
![Backup Text](../img/createNode.jpg "Surface"){: style="width:600px"}

Input           | comment 
----------------|:---------
Geom | Point
CwAttr | Userattributes [optional]
StdAttr | Standardattributes [optional]


Output           | comment 
-----------------|:---------
None | L'élément est généré dans cadwork