<img src="Images/Readme-Title.png" width="525vw">

[![Stars](https://img.shields.io/github/stars/AurelienAudero/KinoDerToten-Pyxel-Game?label=Stars)](https://github.com/AurelienAudero/KinoDerToten-Pyxel-Game/stargazers)
[![Forks](https://img.shields.io/badge/Forks-non%20autoris%C3%A9%20(voir%20la%20licence%20pour%20plus%20d'infos)-red)](LICENSE)
[![Release](https://img.shields.io/github/v/release/AurelienAudero/KinoDerToten-Pyxel-Game?label=Download)](https://github.com/AurelienAudero/KinoDerToten-Pyxel-Game/releases/latest)
-----

**Français** | [English](README_EN.md) | [Español](README_ES.md) | [Deutsch](README_DE.md) | [Italiano](README_IT.md)

## Sommaire
- [Présentation du jeu](#présentation-du-jeu)
- [Fonctionnalités principales du jeu](#fonctionnalités-principales-du-jeu)
- [Installation](#installation)
    - [Configuration requise](#configuration-requise)
    - [Installation de Pyxel et Pygame](#installation-de-pyxel-et-pygame)
    - [Mettre à jour Pyxel et Pygame](#mettre-à-jour-pyxel-et-pygame)
    - [Installation de SDL2 (pour les systèmes Linux)](#installation-de-sdl2-sur-linux)
    - [Comment lancer le jeu](#comment-lancer-le-jeu)
- [Crédits](#crédits)

## Présentation du jeu
**Kino Der Toten : Survivez à l'horreur... ou trépassez !**

Plongez dans un manoir envahi par les morts-vivants et vivez une expérience de survie intense et unique.  
Kino Der Toten est un jeu 2D où votre objectif est simple : survivre le plus longtemps possible.  
Frayez-vous un chemin à travers des hordes de zombies de plus en plus féroces et affûtez vos talents de survivaliste.

Des armes dévastatrices et des secrets bien cachés vous aideront à repousser l'échéance, mais la tension ne fera que croître à chaque minute qui passe. Affrontez des créatures terrifiantes dans des combats épiques qui mettront vos nerfs à rude épreuve.

**Serez-vous le dernier survivant ?**  
**Relevez le défi et prouvez que vous êtes le meilleur !**

## Fonctionnalités principales du jeu
* Un gameplay 2D
* Des vagues de zombies de plus en plus difficiles à vaincre
* Un large choix de contrôles disponibles
* Des combats intenses et palpitants
* Des graphismes et une bande son immersifs

## Installation
### Configuration requise
- [X] Système d'exploitation :
    - [X] Windows Vista ou ultérieur
    - [X] macOS X 10.6 ou ultérieur
    - [X] Linux
- [X] [Python 3.7 ou ultérieur](https://www.python.org/downloads/)
- [X] [Pyxel 2.0.6 ou ultérieur](#installation-de-pyxel-et-pygame)
- [X] [Pygame 2.5.2 ou ultrérieur](#installation-de-pyxel-et-pygame)
- [X] [La dernière version de SDL2 (pour les systèmes Linux)](#installation-de-sdl2-sur-linux)

### Installation de Pyxel et Pygame
Après avoir installé Python, exécuter la commande suivante dans un terminal de commande :
```
pip install pyxel pygame
```

### Mettre à jour Pyxel et Pygame
Si vous avez déjà installé Pyxel et Pygame, exécuter la commande suivante dans un terminal de commande pour le mettre à jour :
```
pip install --upgrade pyxel pygame
```

### Installation de SDL2 (sur Linux)
Si vous utilisez un système Linux, installer SDL2 à l'aide de votre gestionnaire de paquets :  
- apt package manager : `sudo apt-get install libsdl2-dev`  
- dnf package manager : `sudo dnf install SDL2-devel`  
- yum package manager : `yum install SDL2-devel`

### Comment lancer le jeu
- Téléchargez la dernière version stable du jeu [ici](https://github.com/AurelienAudero/KinoDerToten-Pyxel-Game/releases/latest).
- Décompressez l'archive téléchargée
- Ouvrez un terminal de commande dans le repertoire où le jeu se situe
- Exécuter une des commandes suivante : `python3 main.py` ou `python main.py`

## Crédits
- Créateurs du jeu :
    - [Aurélien Audero](https://github.com/AurelienAudero)
    - [Axel Thibert](https://github.com/Oxwerth)
    - [Tony Baca](https://github.com/Thidokachi)
- Remerciements :
    - Amine Ouichen *(pour le système permettant aux tirs de partir dans la direction du viseur)*
    - [Pierrick Perdrieau](https://github.com/Crabiz) *(pour le système permettant aux tirs de partir dans la direction du viseur)*
    - [Timothée Ané](https://github.com/Timothee-Ane) *(pour le système permettant aux tirs de partir dans la direction du viseur)*

"Kino Der Toten - A Pyxel Game" © 2024 by [Aurélien Audero](https://github.com/AurelienAudero), [Axel Thibert](https://github.com/Oxwerth) and [Tony Baca](https://github.com/Thidokachi) is licensed under [CC BY-NC-ND 4.0](https://github.com/AurelienAudero/KinoDerToten-Pyxel-Game/blob/main/LICENSE)
