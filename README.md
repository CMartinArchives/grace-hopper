# Projet HTML/CSS — Reproduction de maquette : Grace Hopper  
Master 2 « Technologies numériques appliquées à l’histoire »  
École nationale des chartes

Projet réalisé par : **Clara Martin**  
Cours de : **Margaux Faure**  
Rendu attendu avant le **28 novembre 2025**

---

## Objet du projet

Ce travail consiste à reproduire une page web en HTML et CSS à partir d’une consigne et d’une capture d’écran fournie.  
L’objectif est de démontrer la maîtrise des bases de l’intégration web, du responsive design, et des conventions professionnelles de structuration du code.

---

## Contenu du projet

Le site repose sur une mise en page structurée autour :

- d’un en-tête comprenant un titre stylisé et un menu de navigation,
- d’un bloc principal en flexbox contenant le texte biographique,
- d’une sidebar de type "infobox" inspirée de Wikipédia,
- d’un rendu visuel respectant la maquette fournie.

Le projet comprend :

- Une organisation des fichiers (HTML, CSS, images, polices),
- Une mise en page responsive utilisant **flexbox**,
- Une sidebar **sticky** sur grand écran,
- Une sidebar replaçant au-dessus du texte sur écran moyen et petit,
- Un menu de navigation avec des ancres internes,
- Un défilement fluide grâce à `scroll-behavior: smooth`,
- Des polices personnalisées intégrées via `@font-face`,
- Une utilisation d’au moins une variable CSS pour les couleurs,
- Des commentaires dans le HTML et dans le CSS expliquant les choix techniques,
- Des effets visuels : hover sur le menu, zoom de l’image au survol.

---

## Architecture recommandée

```bash
grace_hopper/
├── README.md
├── html.html
├── css.css
├── images/
│   ├── grace-hopper.jpg
│   └── Flag_of_the_United_States.svg
└── fonts/
    ├── GreatVibes-Regular.ttf
    ├── Yantramanav-Regular.ttf
    └── Yantramanav-Light.ttf

---

## Mise en ligne (optionnelle)

Le projet peut être publié via GitHub Pages en activant l’hébergement depuis la branche `main` et en plaçant le fichier `html.html` à la racine.  
L’URL prend alors la forme :

https://CMartinArchives.github.io/grace-hopper/
