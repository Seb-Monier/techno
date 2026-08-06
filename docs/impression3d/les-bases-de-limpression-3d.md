# Les bases de l'impression 3D

## Processus
Le processus d'impression 3D comprend trois étapes principales. Tout d'abord, vous devez vous procurer un modèle 3D imprimable. Ensuite, vous devez le préparer pour l'impression, et enfin, la dernière étape est le travail d'impression en lui-même. Voyons tout cela sous un angle général. Puis nous nous pencherons sur les détails.

![Étapes de l'impression 3D](images/prusa/image1.png)

La première étape consiste à obtenir un objet 3D, qui se présente typiquement sous la forme d'un fichier STL. Néanmoins, ce format n'est pas reconnu par les imprimantes 3D et il n'est pas directement imprimable. Pour transformer un fichier STL, vous devez utiliser un outil spécialisé, communément connu sous le nom de slicer (« trancheur »). Il y a différents slicers disponibles sur le marché, certains sont gratuits (PrusaSlicer), d'autres sont payants (Simplify3D) et ils sont habituellement compatibles avec une gamme d'imprimantes limitée, donc vous devez choisir celui qui convient pour votre machine. Vous pouvez importer un fichier STL dans le slicer de votre choix, configurer les paramètres d'impression et exporter le résultat final sous la forme d'un « G-code », qui est concrètement l'objet 3D original découpé en fines couches et converti en une suite de commandes de mouvements reconnue par les imprimantes 3D. De plus, les slicers insèrent des informations additionnelles dans le G-code, comme les informations de température, les paramètres de refroidissement et d'autres choses encore. Le G-code qui en résulte est spécifique à une imprimante, c'est pourquoi les objets 3D sont habituellement partagés sous la forme de fichiers STL — les utilisateurs peuvent ensuite les trancher pour leur imprimante / leur filament individuellement.

Le diagramme ci-dessous décrit les différentes étapes qui rendent possible une impression 3D réussie.

## Se procurer un modèle 3D

En général, vous pouvez obtenir un modèle 3D en utilisant l'un des moyens suivants :

- **Télécharger un modèle 3D sur internet** : [Ou trouver des models 3D](ou_trouver_des_models_3d.md).
- **Créer vos propres modèles** :
- **Scanner en 3D des objets réels**

### Logiciels de création 3D

De nos jours, vous avez le choix parmi une large gamme d'applications de modélisation 3D.  
Il y a des applications simples et faciles à utiliser (et souvent en ligne) comme TinkerCad.  
Vous pouvez essayer la modélisation paramétrique avec OpenSCAD, ou utiliser un outil véritablement professionnel comme le très populaire Autodesk Fusion 360.  
Toutes ces applications vous permettent de créer un modèle et de l'exporter pour de l'impression 3D.

#### Autodesk Fusion 360

Si vous voulez commencer à modéliser des objets fonctionelle , ou bien avec différents éléments destinés à s'assembler, Fusion 360 est une option populaire.   
Les utilisateurs peuvent travailler à la fois CAO (Conception Assistée par Ordinateur), en FAO (Fabrication Assistée par Ordinateur)  , analyser des forces, crer des carte electroniques.   
Fusion 360 offre non seulement une possibilité de modélisation paramétrique, mais permet également la sculpture.  
**[Débuter sur Fusion 360](../fusion360/1er-pas-fusion-360.md)**

#### Tinkercad

Tinkercad est un formidable outil intuitif pour les débutants. Il est gratuit, même s'il est nécessaire de s'enregistrer. Vous pouvez trouver de nombreux tutoriels, des guides ainsi que des conseils en ligne. TinkerCad est construit autour de l'idée d'une bibliothèque de base avec de nombreuses formes, que vous pouvez faire glisser dans la fenêtre principale pour ensuite les modifier. L'application manque de fonctions plus avancées, néanmoins, elle peut importer et éditer un fichier STL déjà existant. Tinkercad est disponible sur [www.tinkercad.com](https://www.tinkercad.com).

![Interface Tinkercad](images/prusa/image14.jpg)


#### Blender

Blender est probablement le meilleur outil de modélisation 3D gratuit aujourd'hui. Il est développé sous une licence open-source et il est disponible pour Windows, Mac et Linux. Il est peut-être un peu complexe pour un débutant, et même sans doute chaotique. Néanmoins, il a sa place dans le cœur de nombreux utilisateurs. Ceux qui ont des ambitions artistiques, et qui n'ont pas besoin de modélisation paramétrique précise, voient en Blender un formidable outil. Sculpture, texture, animation... Blender fait office de couteau suisse parmi les applications de modélisation 3D.

![Interface Blender](images/prusa/image23.jpg)

#### OpenSCAD

OpenSCAD est un projet open-source disponible gratuitement sur [www.openscad.org](https://www.openscad.org). Il propose une approche de la modélisation 3D complètement différente — tout est fait en écrivant du code. L'interface utilisateur est divisée en deux parties. Dans la section de gauche, l'utilisateur définit les objets 3D en les « programmant », tandis que dans la section de droite, une prévisualisation 3D apparait. L'application fonctionne essentiellement sur la base de quelques primitives (cube, cylindre, sphère...) et quelques opérations booléennes (joindre, couper, intersection). Néanmoins, le programme permet également de rédiger un script avancé — vous pouvez utiliser les opérateurs les plus connus, tels que « if », « while », « for », les opérateurs logiques et bien d'autres encore. Si vous vous sentez l'âme d'un programmeur plus que celle d'un artiste, vous pouvez essayer OpenSCAD.

Suivez ce lien pour découvrir en détail comment commencer à créer des modèles avec OpenSCAD : [blog.prusaprinters.org/openscad](https://blog.prusaprinters.org/openscad).

![Interface OpenSCAD](images/prusa/image24.jpg)

Vous pouvez également essayer les applications suivantes :


Sources:
[Prusa](https://www.prusa.com)