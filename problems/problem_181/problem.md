# Problem

## Problem Description

Show that if

\[
{\Omega }^{2}{R}^{3} = {GM}
\]

then \( {u}_{\mathrm{t}}\left( t\right)  = {u}_{\mathrm{r}}\left( t\right)  = \dot{r}\left( t\right)  = 0, r\left( t\right)  = R \) , and \( \omega \left( t\right)  = \Omega \) is an equilibrium point of the equations. Linearize the equations about the equilibrium point and perform a change of coordinates to calculate the linearized system in state space:

\[
\dot{\widetilde{x}} = \left\lbrack  \begin{matrix} 0 & 1 & 0 \\  3{\Omega }^{2} & 0 & {2\Omega } \\  0 &  - {2\Omega } & 0 \end{matrix}\right\rbrack  \widetilde{x} + \left\lbrack  \begin{matrix} 0 & 0 \\  0 & 1/m \\  1/m & 0 \end{matrix}\right\rbrack  \widetilde{u},
\]

\[
\widetilde{y} = \left\lbrack  \begin{array}{lll} 1 & 0 & 0 \end{array}\right\rbrack  \widetilde{x}
\]

where

\[
\widetilde{x} = \left( \begin{matrix} r - R \\  \dot{r} \\  R\left( {\omega  - \Omega }\right)  \end{matrix}\right) ,\;\widetilde{u} = \left( \begin{matrix} {u}_{\mathrm{t}} \\  {u}_{\mathrm{r}} \end{matrix}\right) ,\;\widetilde{y} = r - R.
\]

## Subproblems

1. Identify the physical meaning of the equilibrium conditions for orbital motion.
2. Verify that the given constant-radius motion satisfies the nonlinear equations.
3. Linearize the nonlinear orbital dynamics about the equilibrium point.
4. Derive the Jacobian matrices of the system dynamics.
5. Perform a coordinate transformation to obtain the scaled state variables.
6. Express the linearized dynamics in standard state-space form.
7. Interpret the coupling terms in the linearized model.
8. Explain the significance of the resulting linearized system for orbital control.

## Additional Information

- The model describes planar orbital motion under a central gravitational force.
- The equilibrium corresponds to a circular orbit.
- Linearization is performed about a steady-state orbital solution.
- Control inputs represent radial and tangential thrust components.
- The coordinate transformation rescales angular velocity deviations.

## Constraints

- Linearization must be performed analytically.
- The equilibrium condition must be explicitly verified.
- State and input transformations must be clearly defined.
- The final model must match the specified state-space form.
