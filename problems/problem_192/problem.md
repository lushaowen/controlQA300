# Problem

## Problem Description

The Lotka-Volterra model,

\[
\dot{x}_{1} = r x_{1} - a x_{1} x_{2}
\]

\[
\dot{x}_{2} = ea x_{1} x_{2} - m x_{2}
\]

where \( r, a, e \), and \( m \) are positive constants, is used to model two populations where one of the species is the prey and the other is the predator, e.g. foxes and rabbits. The variable \( x_{1} \) is the prey population, \( x_{2} \) is the predator population, \( r \) is the intrinsic rate of prey population increase, \( a \) is the death rate of prey per predator encounter, \( e \) is the efficiency rate of turning prey into predators, and \( m \) is the intrinsic predator mortality rate.

Calculate the equilibrium points for this model. Assume that all constants are positive, linearize about the equilibrium points, and classify the equilibria as asymptotically stable or unstable. Represent the equations in a block-diagram using integrators and use MATLAB to simulate the predator and prey populations for \( r = 0.05, a = 0.05, m = 0.2 \), and \( e = 0.2 \), with \( x_{1}(0) = 9 \) and \( x_{2}(0) = 1 \). Try other initial conditions and comment on your findings.

## Subproblems

1. Write the Lotka–Volterra equations in vector form.
2. Compute all equilibrium points of the nonlinear system.
3. Linearize the system around each equilibrium point.
4. Determine the eigenvalues of the Jacobian matrices.
5. Classify the stability of each equilibrium.
6. Construct an integrator-based block-diagram representation.
7. Simulate the system for different initial conditions and interpret the results.

## Additional Information

- The model is nonlinear and autonomous.
- Population variables are assumed to be nonnegative.
- No environmental carrying capacity is included.
- MATLAB may be used for numerical simulation and phase-plane analysis.

## Constraints

- All parameters are strictly positive.
- Linearization must be performed using the Jacobian matrix.
- Stability classification must rely on eigenvalue analysis.
- Block-diagrams must use integrators only.
