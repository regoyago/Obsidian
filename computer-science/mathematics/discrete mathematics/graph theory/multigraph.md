in [[graph theory]], a multigraph is a [[graph]] which is permitted to have multiple [[edge]]s, that is, edges tat same the same endpoints, thus, two [[vertex]] can be connected by more than one edge
 
there are two distinct notions of multiple edges
- without own identity: the identity of an edge is defined solely by the two nodes it connects 
	- a multigraph $G$ is an ordered tuple $G:=(V,E)$ with
		- V a [[set]] of vertices or nodes
		- $E$ a [[multiset]] of edges and lines


- with own identity: edges are primitive entities, when multiple edges connect two nodes, these are different edges
	- a multigraph $G$ is an ordered triple $G:=(V,E,r)$ with
		- V a [[set]] of vertices or nodes
		- $E$ a [[multiset]] of edges and lines
		- $r : E \rightarrow \{\{x,y\}:x,y\in V\}$ assigning to each edge an unordered pair of endpoint nodes

mutigraphs are different from [[hypergraph]]s in that the former cannot connect more than 2 vertices with just one edge

#graph_theory 