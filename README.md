# Prim-Fibonacci-Heap
Minimum spanning tree using Prim's algorithm with Fibonacci heap priority queue implementation.

Prim's algorithm is a classical algorithm used to solve the *minimum spanning tree (MST) problem* in a undirected, weighted graph. It is a *greedy algorithm* that shares many common features with the famous Dijkstra's algorithm for single source shortest paths in a weighed graph. Exactly as in the case of Dijkstra's algorithm, the efficiency of Prim's algorithm depends on the implementation of the priority queue that is responsible for the greedy choice performed on each step of the algorithm. The running time complexity of Prim's algorithm with Fibonacci heap implementation of the priority queue is $O(m + n \lg{n})$, where $n$ is the number of vertices and $m$ is the number of edges in the graph.

# fibonacci-heap.jl
Contains the implementation of the Fibonacci heap.

# prim.jl
Contain the implementation of the Prim's algorithm.

# mtrx[n].txt
Contains a $n \times n$ adjacency matrix of an example graph. The file mtrx9.txt contains the example given in the faous book T. H. Cormen, C. E. Leiserson, R. L. Rivest, and C. Stein, Introduction
to algorithms, 4th ed. MIT Press, 2022.
