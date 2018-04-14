# Time-independent Schrödinger Equation in 2D

A presentation for a final project in **Math/ECE 697NA**, **Spring 2017**.

Slides make with Beamer, plots made with matplotlib.

This project explored the use of finite difference methods and sparse eigenvalue solvers to find a numerical solution to the time-independent Schrödinger equation in two dimensions, also known as the particle in a box or the infinite potential well. In this problem the solutions to the equation can be viewed as the eigenfunctions of a Laplacian plus a potential. The discretization of the Laplacian with the finite difference method leads to a sparse symmetric matrix with a small bandwidth. For this problem we are only interested in finding the eigenfunctions corresponding to the smallest eigenvalues. These two properties make the problem well suited for solving with the Lanczos algorithm.

A python notebook showing some of these calculations can be found here (add link).
