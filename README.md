# PrimsMaze
Basic pixel maze generator using Prim's MST Algorithm. 

Inspired from a [Computerphile video](https://www.youtube.com/watch?v=rop0W4QDOUI) on Pathfinding Algorithms, I wanted to test the given code but couldn't find a good pixel maze generator that could also handle large maze-generation.

## In Practice

![alt text](https://github.com/Locrian24/PrimsMaze/blob/master/PrimMaze.png "500x500 Prim Maze")

This is the style of maze generated, with this 500x500 maze being generated in 9.2 seconds. Check out the Computerphile video's [repo](https://github.com/mikepound/mazesolving) to test out their awesome pathfinding alg on these Prim Mazes.

## Usage

prim.py is the main file and should be the one that is run in the console:
```
python3 prim.py <name_of_image>.png <pixel_dimension>
```
