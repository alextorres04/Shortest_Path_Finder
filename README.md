# Shortest_Path_Finder

Overview
This project is a Shortest Path Finder implemented in Python using the Breadth-First Search (BFS) algorithm.
It visualizes the search process in the terminal with the curses library, showing how the algorithm explores the maze step by step until it finds the exit.

⚙️ Features
Maze represented as a 2D grid (# = wall, O = start, X = goal).

BFS algorithm to guarantee the shortest path.

Real-time visualization using curses.

Highlights the explored path in red.

🖥️ Demo
When you run the program, the maze is displayed in the terminal.
The algorithm explores possible paths until it reaches the goal (X), marking the path in red.

---

📂 Code Structure
print_maze() → Draws the maze and highlights the current path.

find_start() → Locates the starting point (O).

find_neighbors() → Finds valid moves (up, down, left, right).

find_path() → Runs BFS to find the shortest path.

---

🚀 How to Run

1. Install the required package for Windows:
   pip install windows-curses

2. Run the script:
   python path_finder.py
   
3. Watch the algorithm explore the maze until it finds the exit.

---

📚 Learning Goals
Practice with queues (queue.Queue) and BFS.

Learn how to use curses for terminal visualization.

Understand pathfinding algorithms in grid-based mazes.

---

✨ Future Improvements
Add random maze generation.

Allow user input for start and end points.

Implement other algorithms (DFS, Dijkstra, A*).
