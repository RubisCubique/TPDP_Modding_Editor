# TPDP Modding Editor

TPDP-ME est un �diteur de fichiers et de projet pour modder le jeu "Touhou Puppet Dance Performance", un jeu maintenant abandonn� par les d�veloppeurs, cod� en C et dont les outils de modding sont tr�s limit�s.
Ce projet actuellement en cours de d�veloppement vise � faciliter le travail avec les diff�rents fichiers � modifier pour que le jeu fonctionne.

Ce projet est un �cho � [TPDP-Dev-Tools](https://github.com/php42/TPDP-Dev-Tools), dont il est grandement inspir�.<br>
TPDP-ME propose �galement un portage en C# de la biblioth�que statique C++ pr�sente dans TPDP-Dev-Tools pour usage personnel.

Il est important de noter que le modding (modifications des fichiers du jeu) est tout � fait l�gal et dans le contexte de ce jeu, permet de rajouter bon nombre de contenu malgr� de nombreuses limitations li�es � la mani�re dont le jeu � �t� con�u.

## Pr�sentation de TPDP

TPDP (Touhou Puppet Dance Performance) est un jeu dit "fan-made" de la s�rie Touhou Project. Ce jeu ressemble fortement � Pok�mon dans son style de jeu et de possibilit�s.

Durant tout ce projet, il sera fait r�f�rence � des "Puppets": Il s'agit du nom donn� aux "Pok�mons" de ce jeu.

Pour modder TPDP, il faut modifier certains fichiers dont les formats varient du PNG, au CSV � du binaire pur. TPDP-ME vise � proposer une interface simple pour modifier ces dits fichiers.

## Fonctionnalit�s

* Ajout de Puppet via l'�diteur (ainsi que la modification de leur statistiques, comp�tences et attaques.)
* Ajout et modification des fichiers *.EVS
* D'autres fonctionnalit�s seront ajout�es au fur et � mesure que le projet se concr�tise.

## Build

Pour build TPDP-ME, il faut:
* Windows 10 (possible avec 7 ou 11 mais non-test�)
* Visual Studio 2022 (possible avec 2019 mais non-test�)
* .NET Framework 8.0

Utilisant WPF, il n'est possible de build que pour Windows.