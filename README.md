# Premier projet Unreal Engine 5

[!IMPORTANT]
Ce dépôt est uniquement destiné à l'équipe de recrutement d'Exail Lannion.

## Sommaire

- [Introduction](#contexte)
- [Fonctionnalités réalisées](#fonctionnalités-réalisées)
- [Améliorations possibles](#améliorations-possibles)
- [Projets futurs & Roadmap](#projets-futurs--roadmap)
- [Utilisation de l'IA](#utilisation-de-lia)

## Contexte

Passionné par le développement logiciel et attiré par l'univers de la 3D, j'ai naturellement commencé à explorer des outils comme Blender, puis plus récemment Unreal Engine.

Après une première initiation à la modélisation l'été dernier, mon objectif était de lier ces compétences au développement en découvrant Unreal Engine. Faute de temps durant l'année universitaire, j'ai dû mettre ce projet de côté. L'opportunité de cette alternance chez Exail a été le déclencheur parfait pour accélérer ma formation sur le logiciel et lier mes compétences académiques à un projet concret.

N'ayant pas de compétences préalables sur Unreal Engine, j'ai réalisé ce mini-projet en m'appuyant sur un tutoriel [Youtube](https://youtu.be/npaSwoy4C0o?si=OhP5qWJ1GtDo8_G7) que j'ai personnalisé et enrichi. 

Je suis conscient que ce rendu reste basique, mais il pose les fondations techniques de mon apprentissage.
Concernant le C++ : Bien que ce projet utilise le système de Blueprints, l'apprentissage du C++ ne sera pas un frein. Je possède de solides bases en langage C ainsi qu'une bonne maîtrise de la Programmation Orientée Objet (POO) acquise via Java et Python. Mon objectif à court terme est de réaliser des micro-projets en C++ pur afin de transposer rapidement ces compétences dans l'environnement Unreal.

## Fonctionnalités réalisées

Configuration initiale : Importation et configuration du template ThirdPerson d'Unreal Engine pour la gestion des déplacements.

Level Design & Environnement : Création d'un terrain avec relief, application de Materials basiques et intégration de ressources végétales (herbes et arbres) récupérées sur la plateforme FAB.

Introduction aux Blueprints : Développement d'une plateforme mobile (mouvement latéral) changeant dynamiquement de couleur au contact du joueur.

Gameplay : Modification du Blueprint de déplacement du personnage pour intégrer une gestion de la vitesse (marche de base et mécanique de sprint).

VFX : Intégration d'un système de particules Niagara déclenché lors du saut du personnage.

## Améliorations possibles

Ajout de retours sonores (SFX) lors du saut ou de l'activation de la plateforme.  

Nettoyage et commentaires des graphes de Blueprints.

## Projets futurs & Roadmap

Ce premier test valide ma compréhension des concepts de base du moteur. Pour la suite de mes vacances et en préparation de l'alternance, je prévois de :

Approfondir ma connaissance du moteur et des possibilitées.

Approfondir l'interaction entre Blender et Unreal Engine (import de pipelines d'animations et de assets personnalisés).

Essayer de développer un prototype de jeu plus complet avec des réels mécaniques.

## Utilisation de l'IA

Dans le cadre de ce projet, j'ai tenté d'utiliser l'IA (Gemini) pour concevoir un système d'interface (UI) dynamique. L'objectif était d'afficher un tutoriel textuel s'adaptant automatiquement au périphérique de l'utilisateur (affichage de la touche Clavier ou Manette selon le dernier input).

Les solutions générées n'étant pas fonctionnelles ou obsolètes par rapport à la version actuelle d'Unreal Engine, j'ai choisi de mettre cette fonctionnalité de côté pour le moment afin de me concentrer sur des mécaniques robustes en Blueprint.
