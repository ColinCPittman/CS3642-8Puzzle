## 8-Puzzle Solver

This project is a Python-based implementation of an[ 8-puzzle solver](https://en.wikipedia.org/wiki/15_puzzle) using various search strategies. 

The goal is to move tiles on a 3x3 grid from a random initial state to a specific target configuration.

### Algorithms Used
* A* Search (Informed)
* Breadth-First Search (BFS)
* Depth-First Search (DFS

### Project Features
* Uses a pre-calculated distance matrix to speed up A* cost calculations.
* Uses a `BoardState` class to track parent-child relationships, costs, and the path taken to reach a solution.
* Has a command-line interface to initialize new boards and select specific search algorithms.
