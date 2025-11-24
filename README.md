Dino endless runner 

🎮 Description

Ce projet est un jeu runner infini 2D, inspiré par un style de jeu « dino run/sidescroller ». Le joueur contrôle un avatar qui avance automatiquement, doit sauter/éviter des obstacles, avec génération procédurale de l’environnement.
Le gameplay met l’accent sur la vitesse qui augmente progressivement et la difficulté qui monte, tout en gardant un cœur simple et addictif.

🧩 Fonctionnalités principales

Défilement automatique de l’environnement (le joueur n’avance pas manuellement)

Sauts / évitement d’obstacles : les obstacles apparaissent de façon procédurale

Vitesse de jeu qui augmente progressivement pour accroître le défi

Score basé sur la distance / le temps / les obstacles franchis

Visuels stylisés (par exemple pixel art ou rendu stylisé)

(Optionnel) Effets de parallaxe pour le fond ou les éléments visuels


📦 Installation & lancement

Clone ce dépôt :

git clone https://github.com/AlexAdowin/Endless-runner-dino-.git


Ouvre le projet dans ton moteur de jeu (par exemple Godot version X.X ou autre selon ce que tu utilises).

Assure-toi que toutes les dépendances / assets sont bien importés (sprites, sons, scripts).

Lance la scène principale (ex : Main.tscn, GameScene, ou équivalent).

Pour tester : joue, observe le score, la montée en vitesse, l’apparition des obstacles.




🎮 Comment jouer

Touche (ou clic) pour sauter : ex. Espace ou “haut”

Le personnage avance automatiquement, évite obstacle.

Plus tu vas loin, plus la vitesse augmente → plus le défi.

L’objectif : obtenir la meilleure distance / score possible.

⚙️ Technique & algorithme de génération

Un module ObstacleGenerator crée des obstacles à intervalles variables, avec position et difficulté croissante.

Vitesse du personnage / caméra = vitesse_initiale + accélération × temps écoulé jusqu’à atteindre un palier max.

Effet de parallaxe : plusieurs couches de fond défilent à vitesses différentes pour donner de la profondeur visuelle.

Gestion des collisions : lorsque le joueur touche un obstacle → fin de partie / reset.

Score = fonction de distance parcourue + bonus éventuels.

🚧 Points à noter / améliorations possibles

Équilibrer la montée en vitesse : trop rapide → frustrant, trop lent → ennuyeux.

Génération d’obstacles : éviter répétitivité ; prévoir variations (hauteur, largeur, espacement).

Ajuster visuels & effets sonores pour feedback joueur (ex. effet de vitesse, changement de fond).

Optimiser performance si ciblé mobile / faible hardware.

Ajout possible : système de bonus, skins, tableau des scores, zones boss, formes du personnage différentes.

