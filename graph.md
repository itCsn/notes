# GRAPH THEORY

## INTRODUCTION

### DEFINITION

The graph theory is the mathematical theory of the properties and applications of graphs (**networks**) in the
real world, since most of the real world situations can be reprensented as a graph problem

**Layman's Definition**
```
A graph is a networks that helps define and visualize 𝑟𝑒𝑙𝑎𝑡𝑖𝑜𝑛𝑠ℎ𝑖𝑝𝑠 between 𝐯𝐚𝐫𝐢𝐨𝐮𝐬 𝐜𝐨𝐦𝐩𝐨𝐧𝐞𝐧𝐭𝐬
```

**Formally** a graph G = (V, E) is a set of vertices V and edges
E where each edges (*u*, *v*) is a connectino between vertices.
*u*, *v* ∈ G.

### TERMINOLOGY

1. **NEIGHBOURS**: a pair of vertices *u*, *v* are neighbours if an edge (*u*, *v*) connects them.
2. **DEGREE**: **degree(*v*)** is equal to the number of edeges connected to *v*, equivalently the
   degree of a vertex is equal to the number of neighbours.
3. **PATH**: sequence of vertices connected by edges.
3. **CYCLE**: a path that starts and ends at the same vertex
4. **CONNECTIVITY**:
```
1.- with respect of two vertices: u, v are connected if a path exist between them.
2.- General grpah: A graph is called connected when all its vertices are connected
	or equivalently, the graph is a cycle
3.- connected components: A subset of a graph that is connected (Vi ⊆ G is connected)
```

### TYPES

1. Undirected graph: Edge has no directions, which means that (*u*, *v*) implies (*v*, *u*)
2. Directed graph: Edges are unidirectional

	> 2.1. directed cycle graph.

	> 2.2. directed acycle graph.

3. Weigted graph: Edges are no treated equally, mostly used in maps, traffic, etc.
4. Trees

### REPRESENTATIONS

How a computer reprensent a graph as a data structure

1. Matrix (**Adjacency Matrix**):
	Aij = {1 for edge (*i*, *j*), 0 otherwise}
2. Sets (**edge set**):
	a set is constructed by all the edges.
3. List (**Adjaency List**) -> _Most Common_:
	a list is made with the values of the vertices where each vertex is map to a list of
	their neighbours
