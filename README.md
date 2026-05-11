# Flappy Bird Clone

Reproduction d'un Flappy Bird en JavaScript natif avec Canvas API.
Projet réalisé dans le cadre d'une formation développeur web.

## Aperçu

Un clone jouable du célèbre Flappy Bird : faites passer l'oiseau entre les tuyaux en cliquant, évitez les collisions et battez votre meilleur score.

## Fonctionnalités

- Physique réaliste : gravité et impulsion au clic
- Animation de l'oiseau via spritesheet (3 frames)
- Génération procédurale des tuyaux
- Détection de collisions
- Sauvegarde du meilleur score en session
- Défilement du fond en boucle

## Concepts abordés

- Canvas API et boucle de rendu avec `requestAnimationFrame`
- Gestion d'un spritesheet avec `drawImage` (9 arguments)
- Physique 2D : gravité, vitesse, position
- Génération et recyclage d'obstacles
- Détection de collisions par boîtes englobantes (AABB)
- Modulo (`%`) pour les animations cycliques

## Demo

Jouer en ligne : [gclaude21.github.io/Flappy-Bird](https://gclaude21.github.io/Flappy-Bird/)



## Contrôles

| Action | Commande |
|--------|----------|
| Lancer la partie | Clic |
| Faire sauter l'oiseau | Clic |

## Stack

- HTML5 Canvas
- JavaScript vanilla (ES6+)
- CSS

## Statut

Projet d'apprentissage, fonctionnel.
