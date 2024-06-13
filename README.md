# vanix

Vanix est la contraction de vanilla (http://vanilla-js.com) et de matrix.
Il s'appuit sur du code vanilla et une matrice dynamique pour générer (côté navigateur) une interaface qui s'adapte à quatre formats d'écrans. De plus, ce qui est dessiné est reproduit à l'identique au pixel près ("pixel perfect"), quelque soit le navigateur.

Le framework est open-source (disponible sous licence MIT).

La création d'un projet doit débuter de préférence par la conception d'une maquette vectorielle (fichier préconfiguré base.svg fourni). Pour ce faire, il est recommandé d'utiliser [inkscape](https://inkscape.org/fr/).

Les fonctionnalités clés de vanix incluent par exemple : 

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
     - Changement d'organisation, d'emplacement de répertoires et de fichiers
     - Persistance de l'application côté navigateur (Progressive Web Apps)
