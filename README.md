# A* Pathfinding Visualizer (Pygame)

A simple grid-based pathfinding visualizer built with Python and Pygame.  
You can draw walls, place start and end points, and watch the A* algorithm find the shortest path.

## Features

- Set start and end points
- Draw barriers with left click
- Erase cells with right click
- Press `SPACE` to visualize the path
- Press `R` to reset the grid

## Requirements

- Python 3.x
- Pygame

Install dependencies:

```bash
pip install pygame
```

## How to Run

```bash
python main.py
```

## How It Works

This visualizer implements the A* pathfinding algorithm using Manhattan Distance as the heuristic (`f(n) = g(n) + h(n)`).  
Movement is limited to up, down, left, and right. Barriers block traversal.

