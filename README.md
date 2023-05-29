# Astar-Path-Planning
In this project we will try to find the cheapest path using A* algorithm.

This is a Python project that implements the A* algorithm for path planning in a grid world. The project uses the Pygame library for graphical display and user interaction. The objective of the project is to find the shortest path between a given start and end point in a grid world that contains obstacles.

The project begins by creating a grid world with randomly placed obstacles, start, and end points. The A* algorithm is then applied to find the shortest path between the start and end points, while avoiding obstacles.

The A* algorithm is implemented using a priority queue to keep track of open nodes, and a set to keep track of closed nodes. The algorithm uses a heuristic function to estimate the cost of reaching the end point from each node, and chooses the path with the lowest cost.

The project also includes a graphical display of the grid world and the path found by the A* algorithm, using different colors to represent different types of nodes (e.g. start, end, obstacles, open, closed, path).

Overall, this project demonstrates the use of the A* algorithm for path planning in a grid world, and provides a visual representation of the algorithm's operation.

Finally the project will print the execution time, cost, and the path if exist.

*Note that you are welcome to change the window size, grid size, and percentage of the obstacles (blocked nodes).
To do that: -
  - window size: In line #256 you will see "WINDOW_SIZE" you can modify it as you like.
  - grid size: In line #262 you will see "SIZE" you can modify it, and number of nodes will be equal to (SIZE*SIZE).
  - percentage of the obstacles: In line #263 you will see "OBSTACLES" you can choose number in range of (0.0 - 1.0).

