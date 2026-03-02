## DAG - Directed Acyclic Graph.
### Topological Sort
lt210
### Cycle Detection
LT 207
#### DFS
use a stack and visited, while iterating, if node appears in stack again, then cycle detected
#### BFS - Kahn's Algorithm 
- each node has in_degree of the number of nodes pointing to it
- iterate and in_degree - 1
- if in_degree = 0, enqueue the node
- keep count of the nodes with in_degree=0, if < total number of nodes, then cycle

### Shortest Path in a DAG
### Longest Path in a DAG
### Dynamic Programming on DAG
