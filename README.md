# Pathfinding Visualizer 

An interactive graphical application built using Python and Pygame that visualizes how different pathfinding algorithms navigate through obstacles to find the shortest path from a start node to an end node.

---

##  Authors
* **Izza Iqbal** 
---

##  Features
* **Interactive Grid:** Click and drag to place start points, end points, and custom barriers/obstacles.
* **Multiple Algorithms:** 
  * **A* Search (`A` key):** Uses heuristics to find the optimal path efficiently.
  * **Breadth-First Search / BFS (`B` key):** Explores paths layer by layer to guarantee the shortest route.
  * **Depth-First Search / DFS (`D` key):** Explores as far as possible along each branch before backtracking.
* **Real-Time Visualization:** Watch the step-by-step progression of node traversal and final path rendering.
* **Clear Board:** Press `C` to reset the grid at any time.

---

##  Tools and Technologies
* **Programming Language:** Python 3.12.4
* **Library:** Pygame 2.6.1 (SDL 2.28.4)
* **Environment:** VS Code

---

##  Getting Started

### Prerequisites
Make sure you have Python installed. You will need to install Pygame to run the application:
```bash
pip install pygame
