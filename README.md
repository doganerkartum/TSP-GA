# Traveling Salesman Problem - Genetic Algorithm Solver

This project is a Python-based solution for the **Traveling Salesman Problem (TSP)** using a **Genetic Algorithm**. It includes comparisons with **Greedy** and **Random** algorithms and visualizes the optimization process over time.

## 📌 About the Project

The Traveling Salesman Problem aims to find the shortest possible route that visits each city once and returns to the starting point. This project demonstrates the use of evolutionary techniques like mutation and tournament selection to approximate the optimal route.

## 🚀 Features

* Reads `.tsp` formatted files
* Implements:

  * Genetic Algorithm with mutation and tournament selection
  * Greedy Algorithm (nearest neighbor)
  * Random Route Generator
* Calculates route lengths using Euclidean distance
* Visualizes:

  * Fitness over epochs (Best, Average, Worst)
  * Prints route sequences and scores

## 🧠 Algorithms Used

* **Genetic Algorithm**

  * Population Initialization
  * Crossover (partial gene inheritance)
  * Mutation (swap)
  * Tournament Selection
  * Epoch-based optimization
* **Greedy Algorithm**

  * Selects nearest unvisited city iteratively
* **Random Algorithm**

  * Shuffles cities randomly

## 📊 Output Example

* Best route sequence (city IDs)
* Route length for Genetic, Greedy, Random algorithms
* Plot: Score trends over epochs

## 📁 Input File Format

This project expects a `.tsp` file with city coordinates like:

```
NODE_COORD_SECTION
1 565.0 575.0
2 25.0 185.0
...
EOF
```

## 🧪 How to Run

```bash
python tsp_solver.py
```

Make sure your `.tsp` file (e.g., `berlin11.tsp`) is in the same directory or specify its path.

## 🛠 Dependencies

* Python 3+
* matplotlib

Install with:

```bash
pip install matplotlib
```

## 👤 Author

Developed by **Doganer Kartum** as a learning project to explore heuristic optimization and algorithmic problem-solving.

---

Feel free to fork, improve or use it in your own work!
