# Jiguzle
A game about jigsaw

## Background
The game is based on jigsaw tiles. There are only 18 unique and legal jigsaw tiles, every tile in a jigsaw is a rotation of one of these 18 base tiles. Jiguzle uses all those 18 tiles only once. 
There are 4 corner tiles, 8 Edge tiles and 6 internal tiles. With those tiles it's possible to build many 4x4 squared frames and then fill them with 4 of the 6 internal tiles.

## Solo rules

### Easy
With corners and edges build one of the possible frames and then try to fill it with the internal tiles.

### Hard
Take 4 of the 6 internal tiles and connect them in a 2x2 square and then try to build a frame around it. Not every combination of internal tiles brings to a possible solution.

### Save and share solutions
Every tile has a letter-number pair on its sides each one with a different orientation. When a solution is found it's possible to save and share it copying the top pair of each tile from top-left to bottom right.
The same solution can be written in 4 different ways depending by the orientation.
#### Example:
![Solution](https://user-images.githubusercontent.com/6410629/176885883-dfcf9bc9-71ad-4136-93d7-332a11faa812.jpg)
A1 J1 E1 B4 I2 Q3 N4 L4 G2 M1 R1 H4 C2 K3 F3 D3

## Battle rules (2 players, or more?)

### Goal
Be the one who place the last tile that completes the square

### How to play

Every player on each turn can do one of the following moves: 
* place a tile (whatever or only a tile that connects with another already in place?)
* switch a tile in place with another one
* remove a tile (not sure, but anyway it's not possible to remove a tile if a tile was already removed during previous 2 turns - one turn per player -).

It's not possible to remove or switch the tile placed by the previous player.
