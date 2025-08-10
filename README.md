# 🚚 Quantum-Inspired VRP Solver

An **evolutionary algorithm** integrating **quantum-inspired mechanisms** to solve the **Vehicle Routing Problem (VRP)**.
This project combines the exploration strength of classical genetic algorithms with concepts from quantum computing to improve search efficiency and solution diversity.

---

## 📌 Overview

The **Vehicle Routing Problem (VRP)** is a combinatorial optimisation challenge where the goal is to determine optimal delivery routes for multiple vehicles starting and ending at a depot, visiting a set of customers exactly once.

In this implementation:

* **Baseline:** A standard evolutionary algorithm (EA).
* **Quantum-Inspired EA (QIEA):** Uses **Q-bit chromosome encoding** and **quantum rotation gates** to guide the search.

The algorithms are compared on solution quality and convergence speed.

---

## 🛠 Features

* Classical EA for VRP as a baseline.
* Quantum-inspired chromosome representation.
* Adaptive quantum rotation operators to balance exploration and exploitation.
* Visualisation of best-found routes and convergence curves.
* Fully self-contained Jupyter Notebook — no extra setup needed.

---

## ⚙️ Requirements

* **Python:** 3.13.5
* **Environment:** Jupyter Notebook (VS Code, JupyterLab, or Anaconda)
* **Libraries:**
    - **Matplotlib**: 3.10.3
    - **NumPy**: 2.3.1

    ```bash
    pip install numpy matplotlib
    ```
    

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/Rodolfocrispim98/Quantum-Inspired-VRP.git
   cd Quantum-Inspired-VRP-Solver
   ```
2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Quantum-Inspired-VRP-Solver.ipynb
   ```
3. Run all cells to reproduce the results (baseline EA and QIEA).

---

## 📊 Outputs

* **Route visualisation:** Shows the optimal routes for each vehicle on a 2D map.
* **Convergence curve:** Tracks cost improvement across generations.

---

## 📚 References

* Han, K. H., & Kim, J. H. (2002). Genetic quantum algorithm and its application to combinatorial optimization. *IEEE Transactions on Evolutionary Computation*, 6(6), 580–593.
* Narayanan, A., & Moore, M. (1996). Quantum-inspired genetic algorithms. *Proceedings of IEEE International Conference on Evolutionary Computation*, 61–66.

