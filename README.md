This mini project is a small exploratory notebook for electrical impedance tomography (EIT) in a simple 2D "head" model.

The project currently:

- builds a 2D triangular mesh for a circular head domain using scikit-fem,
- defines a conductivity distribution with a central high-conductivity inclusion,
- applies simple Dirichlet boundary conditions on the boundary,
- assembles and solves the finite element system for the potential field,
- visualises both the conductivity map and the resulting FEM potential solution.

This serves as a toy forward model for EIT in brain imaging and a starting point for future work on inverse reconstruction (recovering conductivity from boundary measurements).
