# Introduction to Fluid Dynamics in Physics and Astrophysics 
## H.J. van Eerten (2024, CRC Press, Taylor & Francis Group)

This repository includes code and scripts for to accompany the textbook. Currently the following content is included:

### Errata

The file errata.pdf contains a list of typos in the book.

### Various scripts

A number of python scripts to experiment when learning the concepts of the book can be found in the folder various_scripts

### A python version of a hydrodynamics solver

The folder python-hydro contains various iterations of a one-dimensional hydrodynamics solver using the finite volume method as described in chapter 13 of the book. It should run a shock-tube problem out of the box. The solvers are written to convey the concepts of chapter 13 as clearly as possible, rather than to optimize efficiency in e.g. memory management. The simplest implementation can be found in python-hydro-HLL-PCM-FE.py, the most sophisticated in python-hydro-HLLC-PLM-RK3.py. The filename components have the following meaning:

HLL    HLL-solver
HLLC   HLLC-solver
PCM    Piecewise Constant Method
PLM    Piecewise Linear Method
FE     Forward Euker
RK     Runge-Kutta

### A C hydrodynamics solver
