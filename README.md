# Algorithm Design Strategies: Mini-Project

**Name:** Kartik Sharma\
**Roll no. -**  2401420030\
**Course Batch:** B.Tech CSE (Data Science) IBM, 2024-2028\
**Semester:** 4\
**Course/Assignment:** ADA Lab Assignment 2\

## Problem Context
In real-world systems, decision-making and optimization problems arise across various domains such as logistics, finance, healthcare, and network design. This project implements and analyzes core algorithmic paradigms—Divide and Conquer, Greedy Algorithms, and Dynamic Programming—to evaluate their efficiency, scalability, and suitability for different types of computational problems.

## Algorithmic Strategies Implemented
1. **Divide and Conquer:** Implemented Merge Sort (O(n log n)) to demonstrate efficient data sorting by breaking the problem into smaller subproblems.
2. **Greedy Algorithms:** Solved the Fractional Knapsack problem, demonstrating how locally optimal, greedy choices lead to a globally optimal solution when items can be divided.
3. **Dynamic Programming (DP):** Implemented the 0/1 Knapsack problem using tabulation to solve overlapping subproblems efficiently without redundant calculations.
4. **Brute Force (Exponential Growth):** Implemented the Travelling Salesman Problem (TSP) to observe the O(n!) exponential growth in complexity, highlighting the limitations of exact solutions for large inputs.

## Setup & Environment
This project requires **Python >= 3.10** and uses JupyterLab for interactive execution and visualization.

**Required Libraries:**
* `matplotlib` (for performance plotting)
* `numpy` (for dataset generation)
* `memory_profiler` (for profiling memory usage)
* `jupyterlab` (for running the notebook)

**Installation:**
```bash
# Clone the repository
git clone [https://github.com/vidit401/algo-strategies-mini-project-](https://github.com/vidit401/algo-strategies-mini-project-vidit-bansal.git)
cd algo-strategies-mini-project-vidit-bansal

# Create and activate a virtual environment
python -m venv .venv
# Windows: .venv\Scripts\activate
# Mac/Linux: source .venv/bin/activate

# Install dependencies
pip install matplotlib numpy memory_profiler jupyterlab
```

## Usage Instructions
1. Launch JupyterLab by running `jupyter lab` in your terminal.
2. Open `notebooks/algo_strategies_notebook.ipynb`.
3. Run the cells sequentially to execute the algorithms, view the output logs, and generate the performance comparison graphs.

## References
* Cormen, Leiserson, Rivest, Stein - *Introduction to Algorithms* (CLRS)
* [Python Memory Profiler Documentation](https://pypi.org/project/memory-profiler/)
* [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
