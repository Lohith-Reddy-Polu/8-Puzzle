# 8-Puzzle Solver

This is a Python-based 8-Puzzle Solver.

## Overview

This program solves the 8-puzzle problem using the A* search algorithm. Users can input the initial and goal states of the board and get the solution path.

### Input Format

Provide the initial and goal states of the board as space-separated permutations of numbers 0-8, where 0 denotes the empty space.

Example:

**Initial State:**
1 4 2 5 7 6 3 8 0 represents

```
1 4 2 
5 7 6
3 8 
```

**Goal State:**
1 2 3 4 5 6 7 0 8 represents
```
1 2 3
4 5 6
7   8 
```

### File Structure

- `app.py`: Main code for the 8-Puzzle Solver.
- `board.py`: Definition for the Board class representing puzzle states.
- `solver.py`: Implementation of the Agent class for puzzle-solving.

## Usage

1. Run the code on terminal using `python app.py`.
2. Input the initial and goal states as prompted.


