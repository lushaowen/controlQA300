# Problem

## Problem Description

The equations of motion of a rigid body with principal moments of inertia \( J_1 \), \( J_2 \), and \( J_3 \) are given by Euler’s equations:

\[
J_1 \dot{\omega}_1 + \omega_2 \omega_3 (J_3 - J_2) = \tau_1
\]

\[
J_2 \dot{\omega}_2 + \omega_1 \omega_3 (J_1 - J_3) = \tau_2
\]

\[
J_3 \dot{\omega}_3 + \omega_1 \omega_2 (J_2 - J_1) = \tau_3
\]

Represent this set of equations in a block-diagram using only integrators and rewrite the differential equations in state-space form, where

\[
\omega = 
\begin{pmatrix}
\omega_1 \\
\omega_2 \\
\omega_3
\end{pmatrix},
\quad
\tau =
\begin{pmatrix}
\tau_1 \\
\tau_2 \\
\tau_3
\end{pmatrix}
\]

are the angular velocity and torque vectors. The angular velocity \( \omega \) is both the state vector and the output, and \( \tau \) is the input.

## Subproblems

1. Isolate the highest-order derivatives in Euler’s equations.
2. Rewrite each rotational equation in first-order form.
3. Define appropriate state, input, and output vectors.
4. Express the system as a nonlinear state-space model.
5. Identify the nonlinear coupling terms between angular velocity components.
6. Construct a block-diagram using only integrators and algebraic operations.
7. Explain the physical interpretation of the coupling terms in the dynamics.

## Additional Information

- The inertia matrix is diagonal due to the use of principal axes.
- The system dynamics are nonlinear because of the gyroscopic coupling terms.
- Angular velocities are expressed in the body-fixed reference frame.
- No linearization is required for this problem.

## Constraints

- Only integrator blocks may be used to represent dynamics.
- Nonlinear terms must be represented explicitly.
- The state vector and output vector must be identical.
- Each equation must be consistent with rigid-body rotational dynamics.
