# Matrix Decomposition and Linear Solver Algorithms for Symmetric, Positive-Definite Matrices

This research project discusses the stability of matrix decomposition and linear system solver algorithms in Python. We choose to study three common matrix decompositions: QR Factorization (QR), Singular Value Decomposition (SVD), and the Cholesky decomposition (Cholesky). We will focus on the symmetric, positive-definite covariance matrices which frequently arise in machine learning problems. They are generated using Gaussian radial basis function with some additional small noise in the diagonal to mimic real life noisy data.

By conducting numerical studies of comparative backward and forward error analysis of the various decompositions and solvers algorithms for the linear system, we can observe how the size of such matrix affects the stability. We also study the scalability of the algorithms, which includes the run-time required from a computer.

At the end, we concluded the best algorithm is Cholesky decomposition which has minimum level of forward error and comparatively fast runtime when solving a linear system which associated with such covariance matrix.

The notebook with experiments can be found at [Gaussian-Kernel-Decomposition-And-Linear-Solver-w-Optimized-Runtime.ipynb](https://github.com/hailey0huong/kernel_linear_solver/blob/master/Gaussian-Kernel-Decomposition-And-Linear-Solver-w-Optimized-Runtime.ipynb)


