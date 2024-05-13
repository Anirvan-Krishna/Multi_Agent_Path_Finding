# Multi-Agent Path Finding using Conflict Based A* Search

This repository contains code for solving the Multi-Agent Path Finding problem using A* search algorithm and conflict resolution techniques. The main objective is to find optimal paths for multiple agents navigating through a grid with obstacles while avoiding collisions.

## Overview
The provided code implements several key functionalities:
1. **Grid Representation**: Defines a grid environment with obstacles where agents move.
2. **A* Search Algorithm**: Finds the shortest path from a start to a goal position using A* search.
3. **Conflict Detection and Resolution**: Identifies conflicts where agents might collide and resolves them by replanning paths.
4. **Visualization**: Visualizes the grid environment, agent paths, and conflicts using matplotlib.
5. **Path Optimization**: Determines the most efficient order of task execution for a group of robots, minimizing the total time taken.

## Dependencies
The code is written in Python and requires the following dependencies:
- `heapq`
- `matplotlib`
- `itertools`

## Usage
1. Clone the repository:
   ```
   git clone https://github.com/username/repo.git
   ```
Run the provided Jupyter notebook (AIFA_assignment1.ipynb) in a Jupyter Notebook environment (e.g., Jupyter Notebook, Google Colab).

Follow the instructions in the notebook to execute different functionalities, visualize agent paths, and optimize task execution order.

## Code Structure
- **Grid**: Defines the grid environment and methods for grid operations.
- **Node**: Represents a node in the grid for A* search.
- **A*Search**: Implements the A* search algorithm for pathfinding.
- **Conflict Detection and Resolution**: Identifies conflicts between agent paths and resolves them.
- **Visualization**: Provides functions for visualizing the grid, agent paths, and conflicts.
- **Path Optimization**: Optimizes the order of task execution for multiple agents.

# Examples
The notebook includes examples demonstrating the following:

- Finding shortest paths for multiple agents on a grid.
- Resolving conflicts between agent paths.
- Optimizing task execution order for multiple agents.

# References
Sharon, Guni, et al. "*Conflict-based search for optimal multi-agent pathfinding.*" Artificial Intelligence 219 (2015): 40-66.
