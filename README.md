# Efficient and Accurate Simulations of Three-Dimensional Flows Past Obstacles with Vorticity-Based Penalization Methods  
**MSc Thesis in Applied Mathematics – UCLouvain & MIT**

This repository contains the public version of my MSc thesis in **Applied Mathematics**, conducted in collaboration with:

- [Van Rees Lab (MIT)](https://vanreeslab.mit.edu) — focused on vortex-dominated flows and flow control  
- [Thermodynamics & Fluid Mechanics Lab](https://uclouvain.be/en/research-institutes/immc/thermodynamics-and-fluid-mechanics) — focused on multiphysics modeling and scientific computing

---

## Overview

This work addresses the simulation of **three-dimensional incompressible flows past obstacles** using **vorticity-based penalization methods**, which allow for complex boundary enforcement without meshing the obstacle geometry directly.

The simulations are implemented within the evolving **Murphy** framework — a high-performance C++ library for solving **PDEs** on adaptive grids. The design targets multiscale problems with localized features, and aims to minimize computational cost while maintaining accuracy.

### Murphy Framework Highlights

- Structured **octree-based adaptive grids** using `p4est`
- **Finite difference discretization** on collocated grids
- Parallel implementation via **MPI**
- Integration of optimized numerical libraries:
  - **FLUPS** (Poisson solver)
  - **H3LPER** (debug/profiling/logging tools)
- Experimental support for **GPU acceleration**

Unlike unstructured meshing approaches, Murphy leverages **structured adaptivity** to efficiently resolve local flow phenomena, enabling precise modeling of vortex interaction and wake structures.

---

## Potential Applications

Murphy's scalable architecture is well suited for:

- Simulation of multiscale physics in scientific computing  
- Control-oriented PDE modeling and reduced-order modeling  
- Accurate numerical backends for engineering or graphics  
- Complex flows involving fluid–structure interaction

---

## Contact

Feel free to reach out:  
**alexandre.youssef.pro@gmail.com**
