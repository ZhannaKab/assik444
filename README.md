Vertex-Based Graph Algorithms in Java

This project implements graph algorithms Breadth-First Search (BFS) and Dijkstra's Algorithm on an edge-weighted graph using Vertex objects instead of Edge objects, as per assignment requirements.

📌 Project Structure

Vertex.java: Represents a graph vertex with adjacent vertices and edge weights.
WeightedGraph.java: Handles graph structure using vertices and their connections.
Search.java: Abstract base class for graph traversal.
BreadthFirstSearch.java: Implements BFS algorithm.
DijkstraSearch.java: Implements Dijkstra's shortest path algorithm.
Main.java: Demonstrates example usage of the graph and both algorithms.
🧠 Key Concepts

Generic Vertex: Each Vertex<V> holds data and its weighted adjacent vertices.
Graph Representation: Graph is built with a Map<Vertex, List<Vertex>> and weighted edges are stored within the Vertex itself.
Separation of Concerns: Each class has a clear, single responsibility.
✅ How to Run

Compile all .java files.
Run Main.java.
Output will display paths found by BFS and Dijkstra algorithms.
🔄 Example Output

BFS: [A, B, C, D] Dijkstra: [A, B, C, D]

(Output depends on actual edge weights and structure.)

💡 Note

This implementation avoids the use of Edge class and instead focuses on building logic around Vertex objects directly, as required by the assignment.
