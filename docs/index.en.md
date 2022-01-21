# Welcome to RhinoInsideCadwork

RhinoInsideCadwork is a tool that allows you to embed Rhino 7 in cadwork 3D. Take advantage of the surface modeller in your cadwork 3D environment. 

![Referenced GIF](img/beams_curve.gif "beams curve")

## Add-on Download

[food4Rhino - RHINOINSIDE FOR CADWORK 3D](https://www.food4rhino.com/en/app/rhinoinside-cadwork-3d?lang=de)

Food4Rhino is McNeel's community service for plug-ins. Users can find the latest Rhino plug-ins, Grasshopper add-ons, scripts and much more. Furthermore, they can contact the developers and share their applications.

<iframe width="560" height="315" src="https://www.youtube.com/embed/vBh1UHg6ZHQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Grasshopper

Grasshopper is a graphical algorithm editor that integrates with Rhino3D's modelling tools. You use Grasshopper to design algorithms that then automate tasks in Rhino3D.
Grasshopper's visual "plug-and-play" style gives designers the ability to combine creative problem solving with novel control systems through the use of a fluid graphical interface.

![Backup Text](img/process.png "https://modelab.gitbooks.io/grasshopper-primer/content/1-foundations/1-2/2_grasshopper-component-parts.html"){: style="width:800px"}

> 1. The three input parameters of the Circle CNR component.
> 2. the Circle CNR component area.
> 3. the output parameter of the Circle CNR component.

A component needs data to perform its actions, and it usually produces a result. For this reason, most components have a set of nested parameters called inputs and outputs respectively. The input parameters are on the left-hand side and the output parameters are on the right-hand side.

There are a few Grasshopper components that have inputs but no outputs, or vice versa. If a component has no inputs or outputs, it has a jagged edge.

![Backup Text](img/components.png "https://modelab.gitbooks.io/grasshopper-primer/content/1-foundations/1-2/2_grasshopper-component-parts.html"){: style="width:800px"}

## Run RhinoInsideCadwork

RhinoInsideCadwork is started via **Extra -> Rhino Live Link**. 

![GIF](img/run.gif){: style="width:900px"}

## Components

![Backup Text](img/comps.png "BREP"){: style="width:400px"}

### Context-Menu

Some components offer functionalities via the context menu. The context menu is invoked by right-clicking on the icon. <br>

Via the context menu you can

* Select cadwork Elements
* Read axes from Cadwork elements
* Preview 
* Bake Elements <br>

control. 

![Referenced GIF](img/get_elements.gif "get cadwork elements")
