A* Path Planning Algorithm in Pygame
Overview
This project implements a simple A* path planning algorithm within a Pygame environment. The application features a customizable grid for visualizing the pathfinding process.

Features
Initializes a 50 x 50 empty grid.
Left Click Actions:
Place the start node on the first left click.
Place the end node on the second left click.
Place barriers on all subsequent left clicks.
Right Click Actions:
Remove the start, end, or barriers by right-clicking on the respective block.
If the start or end node is removed, it can be repositioned with the next left click.
Clear the entire grid by pressing **c**.
Begin the pathfinding algorithm by pressing the **Space** key.
Usage
To use the application:

Launch the program.
Click on the grid to set the start and end nodes, and to place barriers.
Right-click to remove nodes or barriers as needed.
Press C to clear the grid.
Press Space to execute the A* algorithm and visualize the pathfinding process.

Requirements
Python
Pygame library

Installation
To install the required library, run:
pip install pygame

Conclusion
This project serves as an educational tool for understanding the A* pathfinding algorithm. Feel free to explore and modify the code to enhance your understanding of pathfinding techniques.
