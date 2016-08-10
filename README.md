# spsp
single pair shortest path

the basic idea is using triangle inequality to prune redundant nodes and edges during bfs

U below is Upperbound, L is lower bound.

1   U: Landmarks; L: Landmarks

2   U: Landmarks; L: partitioning

3   U: Hierarchy; L: partitioning

4   U: Landmarks + Hierarchy (to refine); L: partitioning

5   U: Landmarks + Hierarchy (to refine); L: Landmarks + partitioning (Maybe)

6   U: Landmarks' BFS Trees; L: partitioning

7   U: Landmarks' BFS Trees; L: Landmarks
