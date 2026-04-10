# Projet Voxel

Lien github : https://github.com/Mickael-DCR/Voxel

## Intentions gameplay
L'intention de ce prototype est de proposer une boucle de gameplay représentative du projet final :
- On entre dans un donjon
- On tue des monstres faibles
- On meurt contre des monstres forts
- On gagne de l'équipement et on remplit des quêtes pour devenir plus fort
- On tue des monstres plus forts, et on gagne des meilleurs équipements
- On tue le boss final du donjon
- On farm le boss final pour avoir le meilleur équipement possible

## Liste des inputs

| **Action**          | **Bind (Keyboard)** |
|---------------------|---------------------|
| Move                | Z/Q/S/D             |
| Look around         | Move mouse          |
| Attack 1            | Left clik           |
| Attack 2            | Right click         |
| Drink health potion | A                   |
| Open/Close bag      | B                   |
| Open/Close quests   | C                   |
| Equip hovered item  | Right click         |
| Claim quest         | Left click          |
| Delete hovered item | X                   |
| Restart dungeon     | R                   |

## Bugs connus
L'interface ne se focus pas quand on ouvre les panneaux de quête et d'inventaire, il faut cliquer une fois pour naviguer sans faire bouger la caméra.
Quand on ferme un des panneaux, le curseur disparaît même si l'autre panneau reste ouvert.
Il y a un petit rebord invisible devant le spawn qu'il faut contourner.
