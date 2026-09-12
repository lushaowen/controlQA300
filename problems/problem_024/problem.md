# Problem

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

In a previous analysis, a constant motor torque was selected so that the elevator velocity converged to the desired value

\[
\bar{v}_1 = 2\;\mathrm{m/s}
\]

when the system was perfectly balanced (\( m_1 = m_2 \)).

Now assume that the counterweight mass is reduced to

\[
m_2 = 800\;\mathrm{kg},
\]

while the motor torque remains unchanged.

Analyze the resulting velocity response and determine whether the desired velocity is still achieved.  
If not, recalculate a suitable motor torque and compare it with the balanced case.

## Subproblems

1. Determine the steady-state velocity resulting from the original torque.
2. Explain why the desired velocity is no longer achieved.
3. Recalculate the motor torque required to maintain \( \bar{v}_1 = 2\;\mathrm{m/s} \).
4. Derive the new time-domain velocity response.
5. Compare the required torque with that of the balanced system.
6. Comment on the physical significance of the torque difference.
7. Analyze how the decay rate compares with the balanced case.

## Additional Information

- Use the same parameters as in the previous problems except for \( m_2 \).
- The motor torque is constant (open-loop).
- Gravity acts as a constant disturbance.
- No feedback or braking control is applied.
- Viscous friction is present at both inertias.

## Constraints

- All conclusions must be supported analytically.
- Clearly distinguish between transient and steady-state behavior.
- Physical interpretation is required.
- Numerical values must be explicitly computed.
