# Comparative Analysis of Least Squares Optimization Techniques Using Python

This project demonstrates multiple numerical approaches to solving the **Least Squares Problem** and analyzing their accuracy, computational performance, and convergence behavior. Implemented as part of *Numerical Methods in Computer Science*, it explores the mathematical foundations and Python-based implementation of advanced optimization methods.

---

## 📘 Project Overview

The goal of this project is to:
- Implement the **Least Squares Problem** using various decomposition and optimization techniques.
- Compare their **accuracy**, **time efficiency**, and **residual errors**.
- Visualize the **convergence behavior** for Gradient Descent and Newton’s Method.

---

## 🧩 Methods Implemented

### 🔹 Task 1 – Least Squares Problem

Matrix formulations are generated as sparse matrices `A` and `B`.  
The system `Bx ≈ q` is solved using:

1. **QR Decomposition**
2. **Singular Value Decomposition (SVD)**
3. **Truncated SVD**
4. **Cholesky Decomposition**
5. **Gradient Descent**
6. **LGK Decomposition**

Each method is compared in terms of:
- Solution accuracy (`||Bx - q||²`)
- Residual error
- Computation time

### 🔹 Task 2 – Gradient Descent vs. Newton Method

A nonlinear function:

> f(x, y) = ½ × 10⁻³ (x − 1)² + (x² − y)²

is optimized using:
- **Gradient Descent Algorithm**
- **Newton’s Method**

The results include:
- Iterative convergence to the minimum point
- Graphical representation of objective function behavior
- Comparison of convergence rates (Gradient Descent: 100 iterations vs Newton: 14)

---

## 🧮 Technologies & Libraries

- **Python 3**
- `NumPy`
- `SciPy`
- `Matplotlib`
- `scikit-learn` (for Truncated SVD)
- `time` (for performance evaluation)



