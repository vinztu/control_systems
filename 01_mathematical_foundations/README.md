# Chapter 1 — Mathematical Foundations

This chapter covers the mathematical prerequisites for the rest of the course.
Every later chapter draws on at least one of these foundations, so the material here is treated with enough depth to make the connections to control theory explicit.

---

## Sub-Chapters

### 1.1 Linear Algebra
*Topics: Vector Spaces, Subspaces, Linear Maps, Rank and Nullity, Eigenvalues and Eigenvectors, Jordan Normal Form, Norms*

The algebraic backbone of control theory. Introduces vector spaces and the maps between them, develops the spectral theory of matrices (eigenvalues, eigenvectors, diagonalisation, Jordan form), and equips spaces with norms so that size and distance can be measured. Almost every concept in later chapters — from state-space representations to stability analysis — reduces to operations introduced here.

---

### 1.2 Matrix Factorizations
*Topics: LU Decomposition, QR Decomposition, Singular Value Decomposition (SVD), Cholesky Factorization*

Structured decompositions that reveal the geometry and numerical properties of matrices. LU and QR are workhorses for solving linear systems and least-squares problems. The SVD is particularly central to control: it exposes the principal gains of a linear map and underlies system norms, Gramians, and balanced truncation in later chapters.

---

### 1.3 Ordinary Differential Equations and Difference Equations
*Topics: First-order and higher-order ODEs, Linear ODE systems, Matrix exponential, Discrete-time recurrences, z-domain connection*

Describes how state evolves over time in both continuous and discrete settings. Develops the solution of linear ODE systems via the matrix exponential (connecting back to 1.1 Jordan form), and introduces the parallel discrete-time theory via difference equations. These two formalisms are the direct precursors to the state-space models in Chapter 3.

---

### 1.4 Numerical Methods
*Topics: Floating-point arithmetic, Conditioning and numerical stability, Gaussian elimination, Numerical ODE solvers (Euler, Runge-Kutta), Iterative methods*

Bridges the gap between mathematical theory and computational practice. Covers how rounding errors accumulate, how to measure the sensitivity of a problem through condition numbers, and which algorithms are reliable for solving the linear systems and ODEs that arise throughout the course. Essential context for implementing any of the control methods in simulation or on hardware.

---

### 1.5 Probability and Statistics
*Topics: Sample spaces and probability axioms, Random variables, Expectation and variance, Gaussian distribution, Covariance matrices, Law of large numbers and central limit theorem*

Provides the probabilistic language needed for stochastic system models, sensor noise, and estimation. The Gaussian distribution and covariance matrices are the direct inputs to Kalman filtering (Chapter 10) and system identification (Chapter 9). A working understanding of expectation and covariance is also required for stochastic MPC (Chapter 16).

---

### 1.6 Convexity Basics
*Topics: Convex sets, Convex functions, Jensen's inequality, Epigraphs, First- and second-order conditions for convexity*

A concise introduction to the geometry of convex sets and the analytic properties of convex functions. Serves as the direct bridge to Chapter 2 (Optimization Foundations) and reappears throughout the course wherever Lyapunov functions, LMIs, or convex synthesis methods are involved (Chapters 12, 17, 23).

---
