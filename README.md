# Pathfinding Visualizer

Welcome to Pathfinding Visualizer! I created  this tool out of a fascination with pathfinding algorithms and a desire to see them in action with help youtube videos. I hope you find as much enjoyment exploring this visualization as I did building it. You can try it out here (best viewed on Google Chrome!): https://mmohammedh.github.io/Path_Visualizer/

# Explore the Algorithms

This application features the following algorithms:

Dijkstra's Algorithm (weighted): A classic algorithm for finding the shortest path in weighted graphs, guaranteeing the optimal path.

*A Search (weighted)**: Often considered the most efficient pathfinding algorithm, it uses heuristics to find the shortest path faster than Dijkstra's.

Greedy Best-First Search (weighted): A heuristic-driven variant of A* that is faster but does not guarantee the shortest path.

Swarm Algorithm (weighted): A hybrid of Dijkstra's and A*, this algorithm does not guarantee the shortest path but offers a unique approach by balancing exploration and target convergence.

Convergent Swarm Algorithm (weighted): An enhanced version of the Swarm Algorithm, focusing more on heuristic efficiency but still not guaranteeing the shortest path.

Bidirectional Swarm Algorithm (weighted): This algorithm performs the Swarm approach from both the start and target nodes, without guaranteeing the shortest path.

Breadth-First Search (unweighted): A fundamental algorithm that guarantees the shortest path in unweighted graphs.

Depth-First Search (unweighted): Less suitable for pathfinding as it does not guarantee the shortest path and can be inefficient for this purpose.

In addition to these pathfinding algorithms, I've also implemented a Recursive Division Maze Generation algorithm.
