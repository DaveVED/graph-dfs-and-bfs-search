# graph-dfs-and-bfs-search
Graph Cycle Detection (Depth first Search) &amp; Distance Calculation (Breadth First Search) [Python]

## Depth First Search (DFS)
Is a edge based technique. It uses the Stack data structure, performs two stages, first visited vertices are pushed into stack and second if there is no vertices then visited vertices are popped. 

## Breadth First Search (BFS)
Is a vertex based technique for finding a shortest path in graph. It uses a Queue data structure which follows first in first out. In BFS, one vertex is selected at a time when it is visited and marked then its adjacent are visited and stored in the queue. It is slower than DFS.

# Whats Implemented?
## ./dfbf.py
### Cycle Detection (DFS)
The dfs implemenation here tells if there is a cycle in the graph
### Node Distance (BFS)
This bfs tells how far away each node is from the root
## To Run 
### Parameters
```
dfbf.py [input graph you'd like to use] [root node you'd like to use] [debug mode (optional)
```
### Exampele
```
dfbf.py in1.txt a
root key: a
BFS
[('a', 0), ('b', 1), ('c', 1), ('d', 1), ('e', 2), ('f', 2), ('g', 3)]
DFS
cycle in a
cycle in f
```