# Problem: First-Order Velocity Response of an Unbalanced Elevator System

## Problem Description

Consider the elevator dynamic model

\[
\left( J_1 + J_2 + r^2(m_1 + m_2) \right)\dot{\omega}
+(b_1 + b_2)\omega
= \tau + gr(m_1 - m_2),
\]

with the output defined as the vertical velocity of the elevator load

\[
v_1 = r\omega.
\]

Unlike the balanced case, assume now that the counterweight mass is smaller than the elevator load, creating a net gravitational torque.

Using the same parameters as before except for the counterweight mass

\[
m_2 = 800\;\mathrm{kg},
\]

analyze the system dynamics and determine the time response of the elevator velocity.

## Subproblems

1. Write the first-order differential equation governing \( \omega(t) \) when the system is unbalanced.
2. Identify the steady-state angular velocity caused by gravity.
3. Compute the system decay rate.
4. Derive the complete analytical solution for \( \omega(t) \).
5. Express the response in terms of the output velocity \( v_1(t) \).
6. Describe qualitatively how the response differs from the balanced case.
7. Interpret the physical meaning of the nonzero steady-state velocity.

## Additional Information

- The motor torque is set to zero.
- The elevator load is heavier than the counterweight.
- Gravity acts as a constant disturbance input.
- Viscous damping is the only dissipative effect.
- No braking or active control is applied.

## Constraints

- All results must be obtained analytically.
- Clearly distinguish transient and steady-state terms.
- Numerical substitution must be shown.
- Physical interpretation is required alongside mathematical results.
