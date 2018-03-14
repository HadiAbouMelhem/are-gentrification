# Gentrification

Membres : Hadi ABOU MELHEM, Nicolas BOULAUD, Guy-Bom LEE, Dominik NITA

Sujet : Modélisation de la gentrification

Description: Étude du phénomène de gentrification (processus de transformation économique et sociale au
sein d’un quartier au profit d’une classe sociale plus aisée, élévation du niveau de vie par les nouveaux et nouvelles
résident·e·s via la pression des pouvoirs publics, forme de ségrégation poussant à l’absence de mixité
sociale par l’exclusion les classes populaires des quartiers) dans le but de créer un modèle et une simulation dynamique.


## 28/02/2018
- Mise ligne du cahier des charges
- Approfondissement des recherches sur la gentrification : rent-gap theory
- Discussion du choix de modèle entre le modèle de ségrégation de Scheilling et un modèle ayant pour base le prix de l'immobilier
- Réflexion sur la conception

## 07/03/2018
- Choix d'un modèle ayant pour base le prix de l'immobilier, puis implémentation progressive du modèle de ségrégation de Scheilling pour les caractéristiques culturelles
- Réalisation de code informatique pour le cas de prix immobilier fixe : environnement, matrice, prix de l'immobilier représenté par 5 valeurs discrètes, niveau de vie représenté par 5 valeurs discrètes, satisfaction, déménagement

## 14/03/2018
- Fin de la dynamique de déménagement causé par le prix de l'immobilier. 
- Ajout d'une dynamique d'évolution aléatoire du prix de l'immobilier.
- Début des recherches pour implémenter le calcul du prix de l'immobilier par quartier. Nous devons réfléchir à comment implémenter le nombres de transports, le nombre et/ou le niveau des écoles, le patrimoine culturel, le nombre et/ou le type de commerces. Ces variables de départ définissent l'environnement de départ.
- Puis nous devons réfléchir à quelle fréquence un quartier est réhabilité/rénnové, et comment cela influe sur le prix de l'immobilier. Aussi, à quelle fréquence sont crées de nouveaux transports, de nouveaux commerces.
- Nous réflechirons ensuite pour trouver une dynamique qui fait que l'évolution des quartiers voisins influe sur l'évolution d'un quartier. Dans l'environnement de départ, il y aura sans doute un seuil d'écart de prix entre les quartiers voisins.
- Enfin, nous devons définir le typage des prix de l'immobilier qui avantage le plus notre code, tout en étant utile à la validation.
Nous espèrons finir l'implémentation de l'environnement pour la prochaine fois, pour rajouter des paramètres aux déménagements des agents à la séance suivante.







