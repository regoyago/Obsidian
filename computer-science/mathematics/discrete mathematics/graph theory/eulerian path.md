in [[graph theory]], an eulerian trail is a [[trail]] in  a finite graph that visits every [[edge]] exactly once (allowing for revisiting vertices)

similarly, an eulerian circuit or cycle s an eulerian trail that starts and ends on the same [[vertex]]

as postulated by euler's theorem:
	a connected graph has an euler cycle if and only if, every vertex has even degree

for the existence of eulerian trails, it is necessary that zero or two vertices have an odd degree; if there are no vertices of odd degree, all eulerian trails are circuits
a graph that has an eulerian trail but not an eulerian circuit is called semi-eulerian 

an eulerian orientation of an undirected graph $G$ is an assignment of a direction to each edge of $G$ such that at each vertex $v$, the [[indegree]] of $v$ equals the [[outdegree]]

it has the following properties:
- an undirected graph has an eulerian cycle if and only if every vertex has even degree and all of its vertices with nonzero degree belong to a single connected [[subgraph]]
- an undirected graph can be decomposed into edge disjoint cycles if and only if all of its vertices have even degree
- an undirected graph has an eulerian trail if and only if exactly zero or two vertices have odd degree and all of its vertices with nonzero degree  belong to a  single connected subgraph
- a directed graph has an eulerian cycle if and only if every vertex has equal indegree and outdegree and all of its vertices with nonzero degree belong to a single subgraph that represents [[strongly connected relation]]
- a directed graph has an eulerian trail if and only if at most one vertex has $outdegree \ - \ indegree = 1$, at most one vertex has $indegree \ - \ outdegree = 1$, every other vertex has equal indegree and outdegree and all of its vertices with nonzero degree belong to a single connected subgraph

#graph_theory 