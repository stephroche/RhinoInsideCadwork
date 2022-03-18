Folgende Komponenten ermöglichen das generieren von cadwork Elementen. Die Elemente werden als gesperrte Elemente in cadwork dargestellt. Sobald die Elemente "gebacken" werden, wird die Sperrung aufgehoben. Das Backen erfolgt über das Kontextmenü.

![Backup Text](../img/context.jpg "context menü"){: style="width:300px"}

**Bake all to cadwork** gibt alle, mit Grasshopper erzeugten Elemente, frei (Sperrung der Elemente wird aufgehoben). 

## Beam

Die Komponente **Beam** generiert einen Stab in cadwork. 
Nebst dem verpflichtenden Geometrie Input, stehen optional die Möglichkeiten **Axis, CwAttr, StdAttr** zur Verfügung. 

![Backup Text](../img/beam.png "Beam"){: style="width:600px"}

Input           | comment 
----------------|:---------
Geom | Brep closed
Axis | Achssystem [optional]
CwAttr | Userattribute [optional]
StdAttr | Standardattribute [optional]


Output           | comment 
-----------------|:---------
None | Element wird in cadwork generiert

Mit einem Rechtsklick auf das Icon kann im Kontext-Menü die Option **Cadwork Preview, Bake to Cadwork, Bake all to Cadwork** gewählt werden. Dies ermöglicht das Auslesen von Bauteilachsen. 
![Backup Text](../img/beam_bake.png "Beam"){: style="width:600px"}

## Panel

Die Komponente **Panel** generiert eine Platte in cadwork.
![Backup Text](../img/panel.png "Panel"){: style="width:600px"}

Input           | comment 
----------------|:---------
Geom | Brep closed
Axis | Achssystem [optional]
CwAttr | Userattribute [optional]
StdAttr | Standardattribute [optional]


Output           | comment 
-----------------|:---------
None | Element wird in cadwork generiert

## Auxiliary Element

Die Komponente **AuxVol** generiert ein Hilfsvolumen in cadwork.
![Backup Text](../img/auxi.png "Panel"){: style="width:600px"}

Input           | comment 
----------------|:---------
Geom | Brep closed
CwAttr | Userattribute [optional]
StdAttr | Standardattribute [optional]


Output           | comment 
-----------------|:---------
None | Element wird in cadwork generiert

## Drilling

Die Komponente **Drilling** generiert einen Bolzen in cadwork. Die Komponenten benötigt als Input einen **Punkt 1, Punkt 2, Durchmesser**. Die **Bohrungszugabe sowie die Attribute** können optional ergänzt werden. 

![Backup Text](../img/drill.png "Drilling"){: style="width:600px"}

![Backup Text](../img/drilling.png "Drilling"){: style="width:600px"}

Input           | comment 
----------------|:---------
Point_1 | Start Point
Point_2 | End Point
Diameter | Durchmesser [mm]
Supplement | Zugabe Bohrung [mm]
CwAttr | Standardattribute
StdAttr | Standardattribute 


Output           | comment 
-----------------|:---------
None | Element wird in cadwork generiert

## Bauteilachsen

Lokale Bauteilachsen werden über die **Axis** Komponente definiert. 
Es wird ein X-, sowie ein Z-Vector angegeben. 

![Backup Text](../img/axis1.png "Axis"){: style="width:600px"}

Input           | comment 
----------------|:---------
VectorXLocal | {x, y, z}
VectorYLocal | {x, y, z}


Output           | comment 
-----------------|:---------
OutputAxis | Rückgabe der cadwork Ebene

## Create Surface

Die Komponente **AuxVol** generiert ein Hilfsvolumen in cadwork.
![Backup Text](../img/createSurface.jpg "Surface"){: style="width:600px"}

Input           | comment 
----------------|:---------
Geom | Surface
CwAttr | Userattribute [optional]
StdAttr | Standardattribute [optional]


Output           | comment 
-----------------|:---------
None | Element wird in cadwork generiert

## Create Line

Die Komponente **AuxVol** generiert ein Hilfsvolumen in cadwork.
![Backup Text](../img/createLine.jpg "Surface"){: style="width:600px"}

Input           | comment 
----------------|:---------
Geom | Line
CwAttr | Userattribute [optional]
StdAttr | Standardattribute [optional]


Output           | comment 
-----------------|:---------
None | Element wird in cadwork generiert

## Create Node

Die Komponente **AuxVol** generiert ein Hilfsvolumen in cadwork.
![Backup Text](../img/createNode.jpg "Surface"){: style="width:600px"}

Input           | comment 
----------------|:---------
Geom | Point
CwAttr | Userattribute [optional]
StdAttr | Standardattribute [optional]


Output           | comment 
-----------------|:---------
None | Element wird in cadwork generiert