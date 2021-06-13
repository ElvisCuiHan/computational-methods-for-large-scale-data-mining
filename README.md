# Computational Methods for Large-scale Data Mining
This git repo is based on **Dr. Hua Zhou**'s Biostat 257 at UCLA. See the [course website](https://ucla-biostat-257-2021spring.github.io/schedule/schedule.html) for further references. A similar course is taught by **Dr. Lieven Vandenberghe** ([ECE 236B](http://www.seas.ucla.edu/~vandenbe/)) at UCLA.

Projects include:

- **Almost-Fastest algorithms for evaluating log-likelihood functions**.
   1. Beat state-of-art algorithms in Julia **10,000** times for evaluating large-scale linear mixed models.
   2. Modified Sherman-Woodbury-Morrison (SWM) for high dimension matrix inversions.
   3. Modified Determinant formula and SWM for calculating large-scale log-likelihood functions.

- **Various operators for a 100,000,000-observation regression problem**.
- **One million node network analysis with Google Page-Rank algorithm**.
- **Non-linear and convex programming for large-scale longitudinal model**.
- **An expectation-maximization (EM) algorithm for random effect models with millions of observations**.

Topics include:

- Part one: **Algorithms**

  1. Computer arithmetic and elements of Jupyter Notebook.
  2. Introduction to Julia language.
  3. BLAS and LAPACK; NLA on GPU.
  4. Triangular systems including Gaussian elimination (GE) and LU decomposition.
  5. Cholesky decomposition and QR decomposition (Householder, GS and Givens).
  6. Sweep operator (a *North Carolina* invention).
  7. Condition number and theoretical elements of numerical linear algebra.
  8. Iterative solvers including Jacobi, Gauss-Seidel, SOR.
  9. Conjugate gradient method and other Krylov space methods.
  10. Special matrices including Poisson, Wathen, etc.
  11. Algorithms for solving spectral decomposition (SDT) and singular value decomposition (SVD).

- Part two: **Optimization**
  1. Optimization in Julia.
  2. Non-linear programming: Newton-Raphson, Fisher scoring, Gauss-Newtion, Quasi-Newtion, etc.
  3. Karush-Kuhn-Tucker (**KKT**) condition for constrained optimization.
  4. EM algorithm and its variations: ECM, ECME, SEM, Bayesian EM, etc.
  5. Maximization-Minorization (MM) algorithm (a **UCLA** invention).
  6. Convex programming I: Linear programming (LP), Quadratic programming (QP).
  7. Convex programming II: Second order cone programming (SOCP), Semi-definite programming (SDP), Geometric programming (GP).
