# Efficient and Accurate Simulations of Three-Dimensional Flows Past Obstacles with Vorticity-Based Penalization Methods  
**UCLouvain & MIT – MSc Thesis in Applied Mathematics**

This repository contains the public version of my MSc thesis in **Applied Mathematics** at the **École polytechnique de Louvain (UCLouvain)**, carried out in collaboration with:

- the [Van Rees Lab (MIT)](https://vanreeslab.mit.edu), specializing in vortex-dominated flow physics and flow control  
- the [Thermodynamics & Fluid Mechanics Laboratory (UCLouvain)](https://uclouvain.be/en/research-institutes/immc/thermodynamics-and-fluid-mechanics), focusing on multiphysics modelling and scientific computing.

---

## Summary

This work focuses on the accurate simulation of **three-dimensional incompressible flows past obstacles**, using **vorticity-based penalization techniques** within a modern high-performance computational framework.

The thesis contributes to the ongoing development of **Murphy** (“MUltiResolution multiPHYsics”), a general-purpose C++ framework jointly developed by the Van Rees Lab and the TFL Lab. Murphy is designed to solve **Partial Differential Equations (PDEs)** efficiently in multiscale physical problems.

Its architecture is based on:

- Structured collocated grids with **adaptive refinement**
- A block-based **octree grid structure**, using the `p4est` library
- **MPI-based parallelization** for distributed memory computing
- Ongoing **GPU acceleration** for compute-intensive operations
- Integration of high-performance libraries such as:
  - **FLUPS** (fast Poisson solver)
  - **H3LPER** (logging, profiling, debugging)

The goal of Murphy is to provide a **flexible, scalable, and efficient platform** for multiscale physics simulations, with an emphasis on accurate geometry representation and high parallel efficiency.


## Contact

For any questions:  
**alexandre.youssef.pro@gmail.com**
