## Definition

A graph G = (V, E) consists of nonempty set V of vertices(or nodes) and a set E of edges(could be an empty).
Each edge has either one or two vertices associated with it, called endpoints
An edge is said to connect its endpoints.

- Simple graph: each edge connnects two diffrerent vertices and no two edges connect the same pair of vertices.
- Multigraph: may have multiple edges conecting the same two vertices
- Pseudograph: may include loops, as well as multiple edges connecting the same pair of vertices.

- Two vertices 'u' and 'v' in an undirected graph G are called adjacent(or neighbors) in G if there is an edge 'e' between 'u' and 'v'. Such an edge 'e' is called incident with the vertices 'u' and 'v' and 'e' is said to connect 'u' and 'v'.

- The set of all neighbors of a vertex vof G = (V, E), denoted by N(v), is called the neighborhood of v. If A is a subset of V, we denote by N(A) the set of all vertices in G that are adjacent to at least one vertex in A. So, 𝑁(𝐴)=U v∈𝐴 𝑁(𝑣).

- The degree of a vertex in an undirected graph is the number of edges incident with it, except that a loop at a vertex contributes twice to the degree of that vertex. The degree of the vertex 'v' is denoted by deg(v).
