# Premier projet Unreal Engine 5

> [!IMPORTANT]
> Ce dépôt est uniquement destiné à l'équipe de recrutement d'Exail Lannion.

>[!NOTE]
> Je vais publier une autre version (second zip) sans le template ThirdPerson dans les jours à venir !

## Sommaire

- [Introduction](#introduction)
- [Fonctionnalités réalisées](#fonctionnalités-réalisées)
- [Améliorations possibles](#améliorations-possibles)
- [Projets futurs & Roadmap](#projets-futurs--roadmap)
- [Utilisation de l'IA](#utilisation-de-lia)
- [Galerie](#galerie)
- [Crédits](#crédits)

## Introduction

Passionné par le développement logiciel et attiré par l'univers de la 3D, j'ai naturellement commencé à explorer des outils comme Blender, puis plus récemment Unreal Engine.

Après une première initiation à la modélisation 3D l'été dernier, mon objectif était de lier ces compétences au développement en découvrant Unreal Engine. Faute de temps durant l'année universitaire, j'ai dû mettre ce projet de côté. L'opportunité de cette alternance chez Exail a été le déclencheur parfait pour accélérer ma formation sur le logiciel et lier mes compétences académiques à un projet concret.

N'ayant pas de compétences préalables sur Unreal Engine, j'ai réalisé ce mini-projet en m'appuyant sur un tutoriel [Youtube](https://youtu.be/npaSwoy4C0o?si=OhP5qWJ1GtDo8_G7) que j'ai personnalisé et enrichi. 

Je suis conscient que ce rendu reste basique, mais il pose les fondations techniques de mon apprentissage.
Concernant le C++ : Bien que ce projet utilise le système de Blueprints, l'apprentissage du C++ ne sera pas un frein. Je possède de solides bases en langage C ainsi qu'une bonne maîtrise de la Programmation Orientée Objet (POO) acquise via Java et Python. Mon objectif à court terme est de réaliser des micro-projets en C++ pur afin de transposer rapidement ces compétences dans l'environnement Unreal.

## Fonctionnalités réalisées

Configuration initiale : Importation et configuration du template ThirdPerson d'Unreal Engine pour la gestion des déplacements car n'ayant aucune expérience sur le logiciel je voulais une base fonctionnelle pour pouvoir essayer un maximum de choses. (Je vais essayer de refaire un projet sans pour découvrir en détails comment faire)

Level Design & Environnement : Création d'un terrain avec relief, application de Materials basiques et intégration de ressources végétales (herbes et arbres) récupérées sur la plateforme FAB. Ajout d'un mur avec des indications pour le joueur avec un éclairage dessus. Importation d'un model blender dans Unreal Engine (cerf réalisé l'année dernière)

Introduction aux Blueprints : Développement d'une plateforme mobile (mouvement latéral) changeant dynamiquement de couleur au contact du joueur.

Gameplay : Modification du Blueprint de déplacement du personnage pour intégrer une gestion de la vitesse (marche de base et mécanique de sprint).

VFX : Intégration d'un système de particules Niagara déclenché lors du saut du personnage.

Sound effects : Ajout de bruit de pas lorsque le joueur marche (ne fonctionne pas lorsqu'il court), ajout d'un bruit lorsque le joueur monte sur la plateforme

## Améliorations possibles

Nettoyage et commentaires des graphes de Blueprints.

Refaire moi même les Blueprints pour se déplacer du personnage.

## Projets futurs & Roadmap

Ce premier test valide ma compréhension des concepts de base du moteur. Pour la suite de mes vacances et en préparation de l'alternance, je prévois de :

Approfondir ma connaissance du moteur et des possibilitées.

Approfondir l'interaction entre Blender et Unreal Engine (import de pipelines d'animations et de assets personnalisés).

Essayer de développer un prototype de jeu plus complet avec des réels mécaniques.

## Utilisation de l'IA

Dans le cadre de ce projet, j'ai tenté d'utiliser l'IA (Gemini) pour concevoir un système d'interface (UI) dynamique. L'objectif était d'afficher un tutoriel textuel s'adaptant automatiquement au périphérique de l'utilisateur (affichage de la touche Clavier ou Manette selon le dernier input).

Les solutions générées n'étant pas fonctionnelles ou obsolètes par rapport à la version actuelle d'Unreal Engine, j'ai choisi de mettre cette fonctionnalité de côté pour le moment.

J'ai également utilisé Gemini pour corriger et reformuler certaines phrases de ce readme.

## Galerie

![Capture d'écran du projet](https://titouanmoquet.fr/public/images/UE5-proto-img1.png)
![Capture d'écran du projet](https://titouanmoquet.fr/public/images/UE5-proto-img2.png)
![Capture d'écran du projet](https://titouanmoquet.fr/public/images/UE5-proto-img3.png)
![Capture d'écran du projet](https://titouanmoquet.fr/public/images/UE5-proto-img4.png)
![Capture d'écran du projet](https://titouanmoquet.fr/public/images/UE5-proto-img5.png)
![Capture d'écran du projet](https://titouanmoquet.fr/public/images/UE5-proto-img6.png)

## Crédits

Titouan Moquet - 2026

> Portfolio : [titouanmoquet.fr](https://titouanmoquet.fr)

Sound effect : pixabay.com 

