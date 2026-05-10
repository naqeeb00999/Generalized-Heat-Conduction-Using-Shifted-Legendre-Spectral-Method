# Generalized-Heat-Conduction-Using-Shifted-Legendre-Spectral-Method
# Application of Shifted Legendre Polynomial Approximation for Generalized Coupled Heat Conduction Systems

## Author
Muhammad Naqeeb Ul Hassan Naqeebi

Department of Mathematics  
University of Education Lahore (Attock Campus)

Supervised by Dr. Hammad Khalil

---

## Overview

This repository presents a spectral operational matrix method based on shifted Legendre polynomials for solving generalized coupled heat conduction models with boundary constraints.

The method transforms PDE systems into algebraic matrix equations solvable via MATLAB Lyapunov solvers.

---

## Mathematical Model

The generalized coupled heat conduction system:

∂u/∂t = α₁ ∂²u/∂x² + α₂ ∂²v/∂x² + a₀u + a₁v + F(x,t)

∂v/∂t = α₃ ∂²u/∂x² + α₄ ∂²v/∂x² + b₀u + b₁v + G(x,t)

with prescribed initial and boundary conditions.

---

## Numerical Framework

The methodology includes:

- Shifted Legendre basis construction
- Orthogonality implementation
- Operational derivative matrices
- Operational integration matrices
- Transformation matrices
- Matrix reduction to Lyapunov systems
- MATLAB implementation
- Error convergence analysis

---

## Repository Contents

### MATLAB Codes
Numerical implementation scripts.

### Examples
Validation problems with exact solutions.

### Results
Error plots and convergence studies.

### Presentation
MS thesis defense presentation.

### Thesis
Full research document.

---

## Numerical Validation

Validated using:

- Exact vs Approximate comparison
- Maximum absolute error
- RMS error analysis
- Convergence under increasing approximation order

---

## Applications

This framework can be extended to:

- Fractional heat conduction models
- Signal processing PDEs
- Image diffusion equations
- Thermoelastic systems
- Scientific machine learning PDE solvers

---

## Software

MATLAB R2014b+

---

## Citation

If this work assists your research, please cite:

Naqeebi, Muhammad Naqeeb Ul Hassan.
Application of Shifted Legendre Polynomial Approximation Technique for Generalized Coupled Heat Conduction Models with Boundary Constraints.
MS Thesis, University of Education Lahore (Attock Campus), 2026.

---

## Future Research Direction

This work forms the foundation for:

AI-Enhanced Spectral Numerical Methods for Fractional PDEs with Applications in Signal and Image Processing
