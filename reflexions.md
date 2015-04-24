# Pistes et réflexions
## But du jeu
Le but du jeu est d'afficher à l'utilisateur la page qui l'intéresse le plus après être arrivé sur une 404 sur le site.

Pour ça, il manie son personnage en visitant les locaux et quand il sera intéressé par un bureau on le redirigera sur la page du site correspondante.

## Réalisation
Le gameplay doit s'inspirer de Pokémon GameBoy : vue du dessus, un personnage grossier, des graphismes sommaires.

##Technique
Toutes les images utilisées seront des SVG afin d'avoir la plus grande flexibilité possible tout en gardant un support facilement éditable par un graphiste et un développeur.

Framework paper.js utilisé pour gérer les animations et interactions.

**=> comment déplacer le personnage ?**
On défini une fonction onkeydown qui intercepte les flèches (ou ZQSD ?) et qui déplace le fond à l'inverse de la direction demandée, le personnage restant au centre de la zone d'affichage.

Il faudra trouver une animation pour donner l'impression que la personne marche.

** Vérifier qu'on peut facilement rentrer dans un SVG avec jQuery ou autre **
** Trouver une méthode de gestion des messages **
** Dessiner les différents écrans pour voir la place prise et comment tout gérer **
