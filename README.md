# gridify

Gridify est un framework javascript open-source conçu pour la création d'applications web modernes (Progressive Web Apps).
Le projet est développé et maintenu par Cedric Rios et est disponible sous licence MIT.
Il s'appuit sur une grille pour créer des pages élégantes adaptables à tous les écrans et pixel perfect (ce que vous dessinez est reproduit à l'identique).
La création d'un projet doit commencer par l'édition de maquettes vectorielles préconfigurées sous [inkscape](https://inkscape.org/fr/) (fournies).

Les fonctionnalités clés de Gridify incluent par exemple : 

 - Communication full JSON et full Web Socket
 - Animations en cascades
 - Clonage des boutons
 - Utilisation de themes
 - Déclanchement au scroll
 - Import auto-adaptable d'images vectorielles et matricielles
 - Adaptation progressive à la taille est au ratio d'écran
 - Préprocessing relationnel

En chantier :
  
  - Guide d'utilisation
  - Démo : https://web-marseille.com
  - Optimisation :
     - Suppression de l'addEventLister des boutons (remplacés par un seul - via target)
     - Changement d'emplacement de répertoires et de fichiers (Moteur VS Applications individuelles)
     - Persistance de l'application côté navigateur (Progressive Web Apps)
