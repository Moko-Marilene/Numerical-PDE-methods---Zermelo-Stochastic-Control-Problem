---

# HJBI PDE Solver: Finite Differences vs PINNs

## Overview

Numerical solution of a **Hamilton–Jacobi–Bellman–Isaacs (HJBI)** PDE arising in a stochastic optimal control problem.
We compare a classical **finite-difference scheme** with a **Physics-Informed Neural Network (PINN)** in terms of accuracy, stability, and convergence.

---

## Methods

### Finite Differences (Semi-smooth Newton)

* Discretization of the HJBI PDE on a grid
* Solution via a **semi-smooth Newton method**
* Stable and accurate benchmark solution
* Convergence analysis under grid refinement

### Physics-Informed Neural Network (PINN)

* Neural approximation of the value function
* PDE constraints enforced via **automatic differentiation**
* Mesh-free training based on residual minimization
* Boundary/terminal conditions included in loss

---

## Comparison


## Key Results

* Finite differences: **robust and highly accurate for low dimensions**
* PINN: **flexible but sensitive to training dynamics**
* Clear trade-off between numerical reliability (FD) and flexibility (PINN)
