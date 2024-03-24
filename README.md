# A* Pathfinding Algorithm Implementation

This Python script implements the A* pathfinding algorithm using the Pygame library for visualization.This program generates a grid-based environment where an agent navigates from a start point to a destination point while avoiding obstacles.

## Requirements

- Python 3.x
- Pygame

## Installation

1. Clone the repository or download the source code.
2. Install Pygame using pip:
    ```
    pip install pygame
    ```

## File Structure

- `21l-6117_q1.py`: Main Python script containing the implementation of the A* algorithm.
- `README.md`: This README file providing instructions and information about the project.

## Usage

1. Run the script `21l-6117_q1.py` using Python:
2. The program will display a graphical window showing a grid of rectangles representing the environment.
3. Purple rectangles represent open spaces, while black rectangles represent obstacles.
4. The A* algorithm, combined with an evolutionary algorithm, will find the shortest path from a starting point to a destination point on the grid.
5. The path will be marked with yellow rectangles.


## Features

- Grid Environment: Generates a grid-based environment with customizable dimensions and cell size.
- Obstacle Generation: Randomly generates obstacles on the grid based on specified rules.
- A* Pathfinding: Implements the A* algorithm to find the shortest path from the start point to the destination point.
- Evolutionary Algorithm: Utilizes an evolutionary algorithm to enhance the efficiency or effectiveness of the pathfinding process.
- Visualization: Visualizes the grid, obstacles, and the pathfinding process using different colors.


## Colors

- `WHITE`: Background color
- `PURPLE`: Grid cell color
- `BLACK`: Obstacle color
- `YELLOW`: Path color

## Functionality

- The `deploy_grid` function generates the grid environment with obstacles.
- The `a_star_search` function implements the A* algorithm to find the shortest path.
- The `MinHeap` class provides a priority queue implementation for efficient pathfinding.
- The `main` function initializes the grid, runs the A* search, and handles Pygame events.

## Customization

You can customize the following parameters in the code:

- `SCREEN_WIDTH` and `SCREEN_HEIGHT`: Dimensions of the Pygame window.
- `GRID_WIDTH` and `GRID_HEIGHT`: Dimensions of the grid.
- `CELL_SIZE`: Size of each grid cell.
- Obstacle generation rules in the `deploy_grid` function.


## Credits
- This project is created by Ajwa Asif.

## Screenshots of the output
<img width="599" alt="q1 best route ss" src="https://github.com/ItsAjwah/Readme.md/assets/139917879/ba56fe72-565e-4b38-881c-03d9fa33d8df">
<img width="600" alt="q1 best route ss when we run again" src="https://github.com/ItsAjwah/Readme.md/assets/139917879/a53aeff7-dd89-4133-9ec7-5eef0a3894cd">
<img width="599" alt="best route ss after running again" src="https://github.com/ItsAjwah/Readme.md/assets/139917879/bed2839e-7add-4050-9694-48ef05343a77">
