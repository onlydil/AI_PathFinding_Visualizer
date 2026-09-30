# Pathfinding Visualizer

A dynamic and interactive React web app that visualizes classic pathfinding algorithms in action! Built to help understand the inner workings of algorithms like BFS, DFS, Dijkstra, and A*, this project is ideal for learning, showcasing, and impressing.

---

## Features

- Draw walls by clicking and dragging
- Visualize pathfinding from start (green) to end (red)
- Supports multiple algorithms:
  - Breadth-First Search (BFS)
  - Depth-First Search (DFS)
  - Dijkstra's Algorithm
  - A* (A-Star)
- Maze Generation:
  - Random Maze
  - Recursive Division Maze
- Adjustable animation speed
- Reset & regenerate instantly
- Fully interactive grid (mouse-based)

---

## Tech Stack

- **React.js** — Frontend Framework
- **JavaScript / HTML / CSS** — Core Logic & Styling
- **GitHub Codespaces** — Dev Environment (No Tailwind used)

---

## Project Structure

/src

├── algorithms/

│ ├── bfs.js

│ ├── dfs.js

│ ├── dijkstra.js

│ └── aStar.js

│

├── components/

│ ├── Grid.js

│ ├── Node.js

│ └── ...

│

├── mazes/

│ └── recursiveDivision.js

│

├── constants.js

├── App.js

└── index.js


---

## Installation & Usage

### Run on GitHub Codespaces
This project is fully compatible with GitHub Codespaces. Simply:

1. **Create a new Codespace** on this repository
2. In the terminal, run:

```bash
npm install
npm start


