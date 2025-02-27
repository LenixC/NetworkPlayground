# Network Playground

This network playground is a simple, but powerful tool for building intuition
for networks and understanding algorithms and metrics through play.

## How It's Made

**Tech:** HTML, CSS, JS with D3.js

Networks are stored naively as a list of nodes and links. D3 handles the 
implementation of force simulation, so that the network can be dragged and
will spring about. Networks can be built by hand, or they can be generated
according to the Erdős–Rényi model ($G(n, p)$). When a $G(n, p)$ network is
visualized, one can see the probability of a connection for each connection.
This process is not efficient, but the purpose is the visualization itself.

## TODO

- [] Metrics like Degree, Path Length, Diameter, Clustering Coefficient, 
Betweenness, ...
- [] Algorithms like Centrality, Louvain, Modularity Optimization, Pagerank, 
...
