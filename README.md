# Self-Cooling Simulated Annealing (SCSA) & Optimization Benchmarking

This repository provides the official implementation and benchmarking of the **Self-Cooling Simulated Annealing (SCSA)** algorithm, specifically designed for solving **Nonlinear Least Squares** data fitting problems.

[![Paper](https://img.shields.io/badge/Article-CONICET-blue)](https://ri.conicet.gov.ar/handle/11336/278863)
[![Supporting Info](https://img.shields.io/badge/Supporting-Information-green)](https://www.researchgate.net/publication/399911249_Supporting_Information_Self-cooling_Simulated_Annealing_SCSA_algorithm_for_nonlinear_least_square's_data_analysis)

---

## Project Overview

The core of this project is to evaluate the robustness and efficiency of the newly developed **SCSA** algorithm compared to traditional optimization methods. SCSA introduces a dynamic cooling variant that enhances global minima detection in complex parameter-fitting landscapes.

### Implemented Algorithms:
* **Proposed:** Self-Cooling Simulated Annealing (SCSA).
* **Classical:** Gradient Descent, Newton–Raphson, and Levenberg–Marquardt.
* **Stochastic:** Monte Carlo (Acceptance–Rejection) and standard Simulated Annealing.

---

## Repository Structure

| Notebook | Purpose | Key Content |
| :--- | :--- | :--- |
| **[Benchmarking_SCSA.ipynb](./Benchmarking_Self_cooling_Simulated_Annealing.ipynb)** | **Publication Reproducibility** | Reproduces the experiments, comparisons, and figures used as *Supporting Information* for the article. |
| **[Classic_Algorithms.ipynb](./Classic_optimization_algorithms.ipynb)** | **Theory & Visualization** | Demonstrates convergence and local minima detection on 2D test functions (no data fitting). |
| **[DataFitting_Methods.ipynb](./Benchmarking_DataFitting_Methods.ipynb)** | **Practical Application** | Evaluates SCSA against classical approaches using synthetic datasets and analytical fitting functions.

