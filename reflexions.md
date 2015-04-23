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

Gérer le déplacement sur le onFrame si la personne est appuyée sur une touche de déplacement ? Déclencher le déplacement qu'au bout de 10/30 frames consécutives d'appui ?

* on garde le personnage toujours au milieu et le fond se déplace à l'inverse du déplacement demandé du personnage
* on défini une zone dans laquelle le personnage peut se déplacer et quand il arrive aux limites de cette zone, s'il va encore dans cette direction, la caméra se déplace.

Est-ce que paper.js est capable d'afficher des bulles de paroles ? Voir comment les faire.
