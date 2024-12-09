# Orr-Sommerfeld-Equation-Solver
Part of my Term Paper for the course **AM6515-Boundary Layer Stability** at **IIT MADRAS**.
This repository contains a **MATLAB** based code to solve the Orr-Sommerfeld Equation. 
The file *blasius_shooting.m* contains a method to solve the **Blasius profile** by a shooting method and RK-4 intetegration (*rk4.m*). It then solves the Orr-Sommerfeld equation by using a central difference scheme to estimate the second and fourth order derivatives which is used for approximating the Boundary conditions for the system of equations.
The file *plane_poiseulle.m* contains a code for solving the Orr-Sommerfeld equation for a **Plane-Posieulle flow profile** by Spectral Methods using the Chebyshev Polynomial expansions. 
Follow the references for gaining a deeper understanding of how the code works. They helped me a lot.

References:
1) [**Temporal and Spatial Stability Analysis of the Orr-Sommerfeld Equation**](https://www.cdsimpson.net/2015/04/temporal-and-spatial-stability-analysis.html#:~:text=This%20is%20a%20nonlinear%20ordinary,opposite%20boundary%20conditions%20are%20met).
2) [**Chebyshev collocation code for solving two phase Orr-Sommerfeld eigenvalue problem**](https://in.mathworks.com/matlabcentral/fileexchange/48862-chebyshev-collocation-code-for-solving-two-phase-orr-sommerfeld-eigenvalue-problem).
3) **Peter J. Schmid and Dan S. Henningson**, *Stability and Transition in Shear Flows*, *Springer*, 2001
