# AI Search Algorithms

Implementation of BFS and DFS search algorithms in Python for pathfinding and state-space exploration.

## Overview
This project applies uninformed search strategies to grid-based maze solving and puzzle problems, comparing their efficiency in terms of time complexity and memory usage.

## Algorithms
- **BFS (Breadth-First Search)** — explores all neighbors level by level, guarantees shortest path in unweighted graphs
- **DFS (Depth-First Search)** — explores as deep as possible before backtracking, lower memory use but no shortest-path guarantee

## Comparison
| | Time Complexity | Space Complexity | Guarantees Shortest Path |
|---|---|---|---|
| BFS | O(V + E) | O(V) | Yes |
| DFS | O(V + E) | O(V) | No |

## Usage
```bash
python bfs.py

