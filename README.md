# Biological-Network-Analysis

Practice network operations

### 1-1 Basic operations of network (Using network 1, network 2)
  1. calculate the number of nodes and edges
  2. determine if the network is simple or not \
    a. if not simple, list all the self-loops and multi-edges
  3. list all the neighbors of node e and c in the network 1 and 2 respectively \
    a. if not simple, the duplicated neighbors and self-neighbors must be listed
  4. design a function to check if the inputted two nodes are adjacent

### 1-2 Directed graph analysis (Using network 1, network 2)
  1. calculate the in-degree sequence and out-degree sequence of them
  2. check their connectivity, i.e. strongly or weakly connected
  3. calculate the distance between node a and node i
  4. list one subgraph containing at least 5 nodes for each network \
    a. The listed subgraphs must be weakly connected

### 1-3 BFS & DFS (Using network 1)
  1. find one cut-point and one cut-edge
  2. identify two spanning trees of network 1 \
    a. one is DFS tree; another is BFS tree
  3. do following operations on the two identified trees \
    a. edge complementation \
    b. join \
    c. union \
    d. intersection \
    e. difference: (DFS - BFS) and (BFS - DFS)

### 2-1 Adjacency matrix operations (Using network 1)
  1. calculate its density \
  2. output its adjacency and incidence matrix \
  3. find its transitive closure \
  4. Propose the algorithms with pseudocode doing: \
    a. run BFS with adjacency matrix structure \
    b. run DFS with adjacency list structure
