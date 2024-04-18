---
title: Carcassonne
publishDate: 2024-03-25 00:00:00
img: /assets/stock-1.jpg
img_alt: Carcassonne game logo
description: Carcassonne Board Game Programming Project in C Language. In collaboration with Evan ESTREMS.
tags:
  - C language 
  - game coding
  - Pair Programming
---
[Carcassonne Game on github](https://github.com/assalasArab)
# Carcassonne Game

Carcassonne is a board game playable by 2 to 5 players, where the objective is to develop the region surrounding Carcassonne. Each player draws a tile from the available 72 tiles and places it on the game grid. Each tile has 4 sides and a center, representing various landscape elements such as roads, cities, abbeys, and fields. Players have the opportunity to place their tokens on the tiles to accumulate points. To win, you must make the best possible placement of your tokens.

## Our Approach to the Project
### A Penguin Client
The Carcassonne project was developed for a Linux client, therefore it only runs on this system.

### Faithful Representation for Faithful Rendering
In our approach to code the game, we prioritized a faithful representation of the game by creating structures resembling those of the board game, such as Tile, Player, etc...

This allowed us to easily link our code to the board game.

### Two Display Options: Terminal and Graphical
Initially, we chose to create a terminal display, with colors and symbols for tokens, crests, etc...

Until our professor introduced us to a very useful graphical library: Raylib. It is a very accessible graphical library that allows coding of 2D and even 3D games!

## How to Use Our Project
### GitHub
You can download our project via GitHub to explore it and even play a game with your friends!
