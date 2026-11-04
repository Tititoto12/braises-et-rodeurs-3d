# Braises et Rôdeurs — version 3D

Jeu de survie en 3D dans le navigateur : tenir cinq nuits, fabriquer ses outils,
commercer avec les villages et affronter les créatures qui sortent à la tombée du jour.

Tout le jeu tient dans un seul fichier, `index.html`. La logique vient de la version 2D
d'origine ; une couche de rendu Three.js la dessine en 3D.

## Jouer

Ouvre `index.html` dans un navigateur récent (une connexion Internet est nécessaire
au premier chargement pour récupérer Three.js et les polices).

| Touche | Action |
| --- | --- |
| ZQSD / flèches | se déplacer |
| Espace | frapper |
| Maj | esquiver |
| E (maintenir) | parer |
| clic ou R | tirer à l'arc |
| 1 à 5 | pouvoirs |
| C | fabriquer |
| M | carte |
| J | journal |
| T | torche |
| F | manger |
| V | basculer entre la vue 3D et la vue 2D |
| molette | zoom |
| clic droit + glisser | tourner la caméra (clic molette : recentrer) |
| deux doigts (mobile) | tourner et zoomer |

## Ce que fait la vue 3D

- relief (falaises, eau en creux), textures peintes par biome, herbe et feuillages animés par le vent ;
- arbres propres à chaque biome (chênes, bouleaux, pins, sapins enneigés, saules, palmiers…) ;
- maisons à colombages, toits de tuiles, fenêtres qui s'allument la nuit ;
- personnages articulés et animés, habits texturés ;
- soleil qui traverse le ciel, couchant, lune, brouillard teinté selon le biome ;
- effets de combat : arcs de taille, étincelles, ondes de choc, flèches en 3D ;
- météo changeante : pluie et sol mouillé, orages et éclairs, neige en montagne, brouillard,
  brume du matin, ombres de nuages ; lucioles la nuit, feuilles qui tombent ;
- qualité automatique : le rendu s'allège tout seul sur les appareils plus modestes ;
- animations : combos à l'épée (taille, revers, coup final qui fracasse le sol), estoc à la lance,
  roulade, parade, recul quand on est touché ; ennemis qui se fendent, broyeur qui écrase le sol,
  décocheur qui bande son arc, morts qui basculent puis s'enfoncent ;
- pouvoirs : tourbillon de la bourrasque, bille d'arcane lumineuse, cône de flammes, silhouettes
  du pas de l'ombre, cercle de pics de glace et ennemis pris dans la glace ;
- récolte : les arbres tremblent puis tombent, les rochers éclatent, les baies sautent vers toi,
  les coffres crachent leurs pièces ; les constructions sortent de terre ; les objets fabriqués
  apparaissent au-dessus de la tête.
