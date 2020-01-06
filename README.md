# À propos du GameOfLife :U+1F201–U+1F202:

C'est un projet de jeu, de type automate cellulaire. C'est une réecriture en pythonIl fonctionne au tour par tour (par générations), avec des cubes (cellules) respectant trois règles bien définies. Il comporte aussi un système de nombres de tours et un système permettant de choisir un input pour les cubes ou au hasard dans l'espace qui est donné (une grille)

# Téléchargement/Installation

```
Bientôt disponible
```


Description : 

**Le jeu de la vie est un automate cellulaire imaginé par John Horton Conway en 1970 et qui est probablement le plus connu de tous les automates cellulaires. Malgré des règles très simples, le jeu de la vie est Turing-complet.

Le jeu de la vie est un jeu au sens mathématique plutôt que ludique. Bien que n'étant pas décrit par la théorie des jeux, certains le décrivent comme un « jeu à zéro joueur ». 


Règles : 
Le « jeu » se déroule sur une grille à deux dimensions, théoriquement infinie (mais de longueur et de largeur finies et plus ou moins grandes dans la pratique), dont les cases — qu’on appelle des « cellules », par analogie avec les cellules vivantes — peuvent prendre deux états distincts : « vivante » ou « morte ».

À chaque étape, l’évolution d’une cellule est entièrement déterminée par l’état de ses voisines de la façon suivante :

- Si une cellule a exactement trois voisines vivantes, elle est vivante à l’étape suivante.
C’est le cas de la cellule verte dans la configuration de gauche.

- Si une cellule a exactement deux voisines vivantes, elle reste dans son état actuel à l’étape suivante.
Dans le cas de la configuration de gauche, la cellule située entre les deux cellules vivantes reste morte à l’étape suivante.

- Si une cellule a strictement moins de deux ou strictement plus de trois voisines vivantes, elle est morte à l’étape suivante.
C’est le cas de la cellule rouge dans la configuration de gauche.

Ces règles simples permettent de créer des systèmes complexes évoluant ou non sur une période. Il y a des structures stables, récurrentes ou rares.

