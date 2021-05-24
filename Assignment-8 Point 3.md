**3) Analyze the complexity of all your graph behaviors**

Following are the major functions used in Assignment-8 code to implement graph structure according to the
given requirements:

**add_vertex(vertex_name)**

Each vertex will be stored in a dynamic list, and after the insertion we resize adjacency matrix. In reSize() function all the values of adjacency matrix will be initialized with 0.
This function will be
have the average 0(1) time complexity.

**add_edge(source, destination, weight)**

This function will check if the given source and destination vertex exist in the graph, if they do not exist the code will generate an error. If both
vertexes are added in the graph then weight of edge will be stored in the given location. This function will have the average complexity of 0(1).

**shortest_path(source, destination)**
To calculate the shortest_path, I used Dijkstra's Algorithm. For adjacency matrix, the time complexity of this algorithm is O(V^2).

**min_span_tree()**
To find the min_span_tree(), I implemented Prim's algorithm. This algorithm will have the time complexity of O(V^2), V is the number of vertexes in the list.

