# Optimization-Algorithms

## Repository Overview

This repository contains the implementation and benchmarking of several optimization algorithms applied to nonlinear least squares data fitting problems. It includes both classical methods and a recently developed variant called the [Self-Cooling Simulated Annealing (SCSA) algorithm](), which has been published in a recent article.  
Part of the Supporting Information from that publication is generated in one of the notebooks included here.

## Repository Structure

### Benchmarking_Self_cooling_Simulated_Annealing.ipynb
This notebook reproduces the benchmarking experiments presented in the publication [“Self-Cooling Simulated Annealing Algorithm for Nonlinear Least Squares Data Analysis.”](https://ri.conicet.gov.ar/handle/11336/278863)  
It provides detailed results, comparisons, and figures used as [Supporting Information](https://www.researchgate.net/publication/399911249_Supporting_Information_Self-cooling_Simulated_Annealing_SCSA_algorithm_for_nonlinear_least_square's_data_analysis) for the article.

### Classic_optimization_algorithms.ipynb
Demonstrates the behavior and performance of the optimization methods used in the benchmarking process, including Gradient Descent, Newton–Raphson, Levenberg–Marquardt, Monte Carlo Acceptance–Rejection, and Simulated Annealing.  
These methods are applied to standard two-dimensional test functions to visualize convergence and local minima detection, without data fitting.

### Benchmarking_DataFitting_Methods.ipynb
Applies the above methods — including the new SCSA algorithm — to synthetic datasets and a simple analytical function, highlighting the advantages and robustness of SCSA for nonlinear data fitting compared to classical approaches.

