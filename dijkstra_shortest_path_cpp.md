# Dijkstra's Shortest Path Algorithm in C++

This file contains a C++ implementation of **Dijkstra's Algorithm** using two different approaches:

1. `djk_algo` — Implements Dijkstra's algorithm using a `set` to simulate a priority queue.
2. `djk2` — Similar to `djk_algo` but initializes the set with all vertices first.

### Features:
- Graph is represented using an adjacency list.
- Edge weights are taken as input from the user.
- Bidirectional (undirected) graph.
- Prints the shortest distance from the source to all other vertices.
- Computes and prints the minimum distance between given source and destination.

### Usage:
Compile and run the program. Provide:
- Number of vertices and edges.
- Edge connections and their weights.
- Source and destination vertices.

The program outputs:
- Distance from the source to all nodes.
- Shortest path distance from source to destination using both algorithm implementations.
