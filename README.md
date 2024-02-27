# TPDP Modding Editor

TPDP-ME est un éditeur de fichiers et de projet pour modder le jeu "Touhou Puppet Dance Performance", un jeu maintenant abandonné par les développeurs, codé en C et dont les outils de modding sont très limités.
Ce projet actuellement en cours de développement vise à faciliter le travail avec les différents fichiers à modifier pour que le jeu fonctionne.

Ce projet est un écho à [TPDP-Dev-Tools](https://github.com/php42/TPDP-Dev-Tools), dont il est grandement inspiré.<br>
TPDP-ME propose également un portage en C# de la bibliothèque statique C++ présente dans TPDP-Dev-Tools pour usage personnel.

Il est important de noter que le modding (modifications des fichiers du jeu) est tout à fait légal et dans le contexte de ce jeu, permet de rajouter bon nombre de contenu malgré de nombreuses limitations liées à la manière dont le jeu à été conçu.

## Présentation de TPDP

TPDP (Touhou Puppet Dance Performance) est un jeu dit "fan-made" de la série Touhou Project. Ce jeu ressemble fortement à Pokémon dans son style de jeu et de possibilités.

Durant tout ce projet, il sera fait référence à des "Puppets": Il s'agit du nom donné aux "Pokémons" de ce jeu.

Pour modder TPDP, il faut modifier certains fichiers dont les formats varient du PNG, au CSV à du binaire pur. TPDP-ME vise à proposer une interface simple pour modifier ces dits fichiers.

## Fonctionnalités

* Ajout de Puppet via l'éditeur (ainsi que la modification de leur statistiques, compétences et attaques.)
* Ajout et modification des fichiers *.EVS
* D'autres fonctionnalités seront ajoutées au fur et à mesure que le projet se concrétise.

## Build

Pour build TPDP-ME, il faut:
* Windows 10 (possible avec 7 ou 11 mais non-testé)
* Visual Studio 2022 (possible avec 2019 mais non-testé)
* .NET Framework 8.0

Utilisant WPF, il n'est possible de build que pour Windows.