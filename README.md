# vanix

Vanix est un framework javascript open-source conçu pour la création d'applications web orientées avant tout vers l'élégance et la performance.
Le projet est développé, maintenu rendu et disponible sous licence MIT.
Il s'appuit sur une grille pour créer des pages adaptables à tous les écrans et pixel perfect (ce que vous dessinez est reproduit à l'identique au pixel près).
La création d'un projet doit débuter de préférence par la conception d'une maquette vectorielle (fichier préconfiguré base.svg fourni). Pour ce faire, il est recommandé d'utiliser [inkscape](https://inkscape.org/fr/).

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
