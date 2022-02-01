# Bienvenue dans RhinoInsideCadwork

RhinoInsideCadwork est un outil qui permet d'intégrer Rhino 7 dans cadwork 3D. Profitez des avantages du modeleur de surface dans votre environnement cadwork 3D.

![Referenced GIF](img/beams_curve.gif "beams curve")

## Add-on Download

[food4Rhino - RHINOINSIDE FOR CADWORK 3D](https://www.food4rhino.com/en/app/rhinoinside-cadwork-3d?lang=de)

Food4Rhino est le service communautaire de McNeel pour les plug-ins. Les utilisateurs y trouvent les derniers plug-ins de Rhino, des modules complémentaires de Grasshopper, des scripts et bien plus encore. Ils peuvent également prendre contact avec les développeurs et partager leurs applications.

<iframe width="560" height="315" src="https://www.youtube.com/embed/vBh1UHg6ZHQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Grasshopper

Grasshopper est un éditeur graphique d'algorithmes intégré aux outils de modélisation de Rhino3D. Vous utilisez Grasshopper pour concevoir des algorithmes qui automatisent ensuite des tâches dans Rhino3D.
Le style visuel "plug-and-play" de Grasshopper donne aux concepteurs la possibilité de combiner des solutions créatives aux problèmes avec des systèmes de règles inédits en utilisant une interface graphique fluide.

![Backup Text](img/process.png "https://modelab.gitbooks.io/grasshopper-primer/content/1-foundations/1-2/2_grasshopper-component-parts.html"){: style="width:800px"}

> 1. les trois paramètres d'entrée du composant Circle CNR.
> 2. la zone du composant Circle CNR.
> 3. le paramètre de sortie du composant Circle CNR.

Un composant a besoin de données pour pouvoir effectuer ses actions, et il fournit généralement un résultat. C'est pourquoi la plupart des composants ont une série de paramètres imbriqués, appelés entrées ou sorties. Les paramètres d'entrée se trouvent sur le côté gauche, les paramètres de sortie sur le côté droit.

Il existe quelques rares composants de Grasshopper qui ont des entrées mais pas de sorties, ou l'inverse. Si un composant n'a ni entrées ni sorties, il a un bord dentelé.


![Backup Text](img/components.png "https://modelab.gitbooks.io/grasshopper-primer/content/1-foundations/1-2/2_grasshopper-component-parts.html"){: style="width:800px"}

## Run RhinoInsideCadwork

RhinoInsideCadwork est lancé via **Extra -> Rhino Live Link**.

![GIF](img/run.gif){: style="width:900px"}

## Composants

![Backup Text](img/comps.png "BREP"){: style="width:400px"}

### Menu contextuel

Certains composants proposent des fonctionnalités via le menu contextuel. Le menu contextuel est appelé par un clic droit sur l'icône. <br>

Le contexte permet de contrôler les fonctions suivantes.

* Sélectionner des éléments Cadwork
* Lire les axes des éléments Cadwork
* Aperçu 
* Bake Elements <br>


![Referenced GIF](img/get_elements.gif "get cadwork elements")
