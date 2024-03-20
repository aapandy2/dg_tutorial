# DG tutorial

A simple tutorial implementing a discontinuous Galerkin (DG) scheme to solve the 1D scalar advection equation.

`DG_tutorial_p1.ipynb` works out a _modal_ DG scheme in the basis of monomials, keeping only the first two basis functions (i.e., the solution is taken to be piecewise linear in space).

`DG_tutorial_p2.ipynb` implements a _nodal_ DG scheme using the basis of Lagrange polynomials with Legendre collocation points.
