# Willkommen zu RhinoInsideCadwork

RhinoInsideCadwork ist ein Tool, welches die Einbettung von Rhino 7 in cadwork 3D ermöglicht. Nutzen Sie die Vorteile des Flächenmodellieres in ihrer cadwork 3D Umgebung. 

![Referenced GIF](img/beams_curve.gif "beams curve")

## Add-on Download

[food4Rhino - RHINOINSIDE FOR CADWORK 3D](https://www.food4rhino.com/en/app/rhinoinside-cadwork-3d?lang=de)

Food4Rhino ist McNeels Community-Dienst für Plug-ins. Anwender finden hier die neuesten Rhino-Plug-ins, Grasshopper-Add-ons, Scripts und vieles mehr. Darüberhinaus können sie mit den Entwicklern Kontakt aufnehmen und ihre Anwendungen teilen.

<iframe width="560" height="315" src="https://www.youtube.com/embed/vBh1UHg6ZHQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Grasshopper

Grasshopper ist ein grafischer Algorithmus-Editor, der in die Modellierungswerkzeuge von Rhino3D integriert ist. Sie verwenden Grasshopper, um Algorithmen zu entwerfen, die dann Aufgaben in Rhino3D automatisieren.
Der visuelle "Plug-and-Play"-Stil von Grasshopper gibt Designern die Möglichkeit, kreative Problemlösungen mit neuartigen Regelsystemen durch die Verwendung einer fließenden grafischen Oberfläche zu kombinieren.

![Backup Text](img/process.png "https://modelab.gitbooks.io/grasshopper-primer/content/1-foundations/1-2/2_grasshopper-component-parts.html"){: style="width:800px"}

> 1. Die drei Eingangsparameter der Komponente Circle CNR.
> 2. Der Kreis CNR-Komponentenbereich.
> 3. Der Ausgangsparameter der Komponente Circle CNR.

Eine Komponente benötigt Daten, um ihre Aktionen ausführen zu können, und sie liefert in der Regel auch ein Ergebnis. Aus diesem Grund haben die meisten Komponenten eine Reihe von verschachtelten Parametern, die als Inputs bzw. Outputs bezeichnet werden. Die Eingabeparameter befinden sich auf der linken Seite, die Ausgabeparameter auf der rechten Seite.

Es gibt einige wenige Grasshopper-Komponenten, die Eingänge, aber keine Ausgänge haben, oder andersherum. Wenn eine Komponente keine Eingänge oder Ausgänge hat, hat sie eine gezackte Kante.

![Backup Text](img/components.png "https://modelab.gitbooks.io/grasshopper-primer/content/1-foundations/1-2/2_grasshopper-component-parts.html"){: style="width:800px"}

## Run RhinoInsideCadwork

RhinoInsideCadwork wird über **Extra -> Rhino Live Link** gestartet. 

![GIF](img/run.gif){: style="width:900px"}

## Komponenten

![Backup Text](img/comps.png "BREP"){: style="width:400px"}

### Kontext-Menü

Einige Komponenten bieten Funktionalitäten über das Kontext-Menü an. Das Kontext-Menü wird mittels Rechtsklick auf das Icon aufgerufen. <br>

Über das Kontext-Menü lassen sich

* Cadwork Elemente auswählen
* Achsen von Cadwork Elementen auslesen
* Preview 
* Bake Elements <br>

steuern. 

![Referenced GIF](img/get_elements.gif "get cadwork elements")
