# FEM Learning Roadmap

This repository is for learning the **Finite Element Method (FEM)** from the very beginning, then gradually building toward nonlinear FEM topics needed for a master thesis:

- **Geometric nonlinearity** (large deformation)
- **Force nonlinearity** (follower force)

## Goal

Build a strong and logical foundation in FEM, then solve increasingly complex nonlinear problems in a step-by-step way.

## Learning Path

### 1) Foundation (Beginner)
- Basic mathematics used in FEM (vectors, matrices, weak form ideas)
- 1D bar and spring elements
- Assembly of global stiffness matrix
- Boundary conditions and linear static solution

### 2) Core FEM Skills (Intermediate)
- Beam and 2D elements
- Shape functions and numerical integration (Gauss quadrature)
- Stress/strain recovery
- Verification with simple benchmark problems

### 3) Nonlinear FEM (Advanced)
- Material vs. geometric nonlinearity (clear distinction)
- Incremental-iterative solution methods (Newton-Raphson)
- Large deformation kinematics and tangent stiffness updates
- Follower force definition and consistent load linearization

### 4) Thesis-Oriented Problems
- Start from small nonlinear benchmark examples
- Increase complexity in geometry and loading step by step
- Compare numerical results with references/literature
- Document assumptions, convergence behavior, and limitations

## Repository Direction

The repository should evolve in a logical sequence:
1. Simple linear FEM examples
2. Verified intermediate examples
3. Nonlinear geometric examples (large deformation)
4. Nonlinear loading examples (follower force)
5. Combined challenging thesis-level cases
