# Shortest Path Algorithms - Graph Analysis with Python

This project demonstrates the application of two popular pathfinding algorithms — **Dijkstra's Algorithm** and **A\*** (A-star) — to compute the shortest path in a weighted undirected graph. 
The analysis is based on a visual representation of a network, where each node and edge represents a possible connection and cost.

## 📁 Files Included

- `Marco_AI_CA2.ipynb`: Jupyter notebook implementing Dijkstra's and A* algorithms with step-by-step logic and output.
- `graph1.PNG`: Original graph used for pathfinding.
- `shortest_path.PNG`: Visualization of the shortest path found using Dijkstra's or A*.
- `Distance_C.PNG`, `Distance_G.PNG`, `Distance_L.PNG`, `Distance_N.PNG`, `Distance_S.PNG`: Step-by-step screenshots showing updates to distance estimates.
- `c52ae0e9-4c97-4420-ad51-ee0af21fe1b8.png`: Final result or path representation.

## 🔍 What This Project Does

- Parses a weighted graph from an image.
- Implements:
  - **Dijkstra’s Algorithm**: Explores all possible paths using greedy selection.
  - **A\*** (A-star) Algorithm: Uses both actual distance and heuristic (estimated cost to goal) to guide the search more efficiently.
- Uses visual aids to highlight how distances and paths are updated in each step.
- Outputs the final shortest path and its total cost.

## 📌 Key Concepts

- **Graph traversal**
- **Greedy algorithms**
- **Heuristic search**
- **Priority Queue (for node selection)**
- **Data visualization for learning and explanation**

## 🧠 Skills Demonstrated

- Python programming (control flow, data structures, priority queues)
- Implementation of Dijkstra and A* algorithms
- Debugging with visual feedback
- Jupyter Notebook for combining code, results, and explanations

## 🛠 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/shortest-path-dijkstra-a-star.git
   cd shortest-path-dijkstra-a-star
   ```

2. Open the notebook:
   ```bash
   jupyter notebook Marco_AI_CA2.ipynb
   ```

3. Follow the notebook to explore both algorithm implementations and visualizations.

## 📷 Sample Output

Here's a sample of the result:

![shortest_path_graph](https://github.com/user-attachments/assets/5f57d222-5483-4064-9df1-488bc20e713e)


## 📚 References

- Dijkstra, E. W. (1959). A note on two problems in connexion with graphs.
- Hart, P. E., Nilsson, N. J., & Raphael, B. (1968). A formal basis for the heuristic determination of minimum cost paths.
- https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm
- https://en.wikipedia.org/wiki/A*_search_algorithm

