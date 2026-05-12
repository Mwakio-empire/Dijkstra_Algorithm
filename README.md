# Dijkstra_Algorithm
##Summary
A depiction of the Dijkstra_Algorithm in action for areas around Multimedia university of kenya

## Title
Finding the Shortest Path Between Nairobi Matatu Stages Using Dijkstra’s Algorithm

## Objective
This project models Nairobi matatu stages as a weighted graph. 
The stages are represented as nodes(vertices), while the roads connecting them are represented as edges with weights(distance in kilometers). 
Dijkstra’s Algorithm is then used to determine the shortest path between two stages.

## Nodes Used
1. MMU
2. Ongata Rongai
3. Bomas
4. Langata
5. CBD
6. Ngara
7. Pangani
8. Muthaiga
9. Kasarani
10. Roysambu
11. TRM
12. Githurai
13. Westlands
14. Parklands


## Explanation of the Program

### Data Structure Used
- Graph
- Priority Queue (Heap)
- Dictionary

### Why Dijkstra’s Algorithm?
Dijkstra’s Algorithm is efficient for finding the shortest path in weighted graphs with non-negative distances.

### Time Complexity
The implementation uses a Min Heap (Priority Queue), making the complexity:

O((V + E) log V)

Where:
- V = Number of vertices
- E = Number of edges

This is more efficient than the basic implementation using arrays.



