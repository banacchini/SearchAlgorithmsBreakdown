# SearchAlgorithmsBreakdown
This project explores the implementation and empirical analysis of various search algorithms within the classic Pacman environment. The objective is to test how these algorithms perform in guiding Pacman through different mazes to collect food dots. The project focuses on comparing search algorithms based on execution time, expanded nodes, and path length.

Pacman Environment source code: [UC Berkeley](https://ai.berkeley.edu/project_overview.html)

![Heatmap of an A* algorithm in a maze](https://github.com/banacchini/SearchAlgorithmsBreakdown/blob/main/cavesManhattan.png)

### Algorithms Compared:
- **Depth-First Search (DFS)**
- **Breadth-First Search (BFS)**
- **Uniform Cost Search (Dijkstra)**
- **A* Algorithm (with Euclidean and Manhattan Heuristics)**

![Comparison of Nodes Expanded by investigated algorithms](https://github.com/banacchini/SearchAlgorithmsBreakdown/blob/main/timeComparisson.png)

### Features:
- Comparison of algorithm performance across various maze complexities
- Introduction of diagonal movement and new admissible heuristic functions
- Empirical studies with detailed performance metrics like execution time, number of expanded nodes, and path cost


### How It Works:
The project compares each search algorithm in multiple custom-designed mazes with increasing complexity. In each scenario, we analyze:
- **Execution Time**: How fast each algorithm finds a solution
- **Expanded Nodes**: The number of nodes explored during the search
- **Path Length**: The total steps taken by Pacman to reach the goal
