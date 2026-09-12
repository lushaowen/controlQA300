# Problem

## Problem Description

A schematic diagram of an elevator system is shown in Fig. 2.18(b).  
The system consists of two rotating inertias \( J_1 \) and \( J_2 \) connected by an inextensible belt over a pulley of radius \( r \). Two masses \( m_1 \) and \( m_2 \) are attached to the belt, where \( m_1 \) represents the elevator load and \( m_2 \) is a counterweight.

The driving motor applies a torque \( \tau \) to inertia \( J_1 \).  
Viscous friction torques proportional to angular velocity act on both inertias, characterized by coefficients \( b_1 \) and \( b_2 \).

Proceed to derive a simplified dynamic model describing the motion of the entire elevator system, and show that it can be represented by

\[
\left( J_1 + J_2 + r^2(m_1 + m_2) \right)\dot{\omega}
+(b_1 + b_2)\omega
= \tau + gr(m_1 - m_2),
\]

with kinematic relations

\[
v_1 = r\omega, \qquad v_2 = -r\omega.
\]

Finally, explain why it is advantageous for the counterweight mass to match the elevator load as closely as possible.

## Subproblems

1. Write the rotational equations of motion for inertias \( J_1 \) and \( J_2 \).
2. Use belt constraints to relate the angular velocities of the two inertias.
3. Derive the translational equations of motion for masses \( m_1 \) and \( m_2 \).
4. Combine the rotational and translational equations into a single dynamic equation.
5. Interpret each term in the resulting equation physically.
6. Explain the role of the counterweight in reducing motor effort and gravitational disturbance.

## Additional Information

- The belt is massless, inextensible, and does not slip.
- Gravity acts downward with acceleration \( g \).
- The system operates in the linear regime.
- Positive angular velocity corresponds to upward motion of mass \( m_1 \).
- All friction is modeled as viscous.

## Constraints

- All derivations must be shown step by step.
- Clearly state sign conventions and physical assumptions.
- Express the final model using a single generalized coordinate.
- Provide physical interpretation, not just algebraic manipulation.
