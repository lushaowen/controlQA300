# Problem: Open-Loop Torque Selection for Desired Elevator Velocity

## Problem Description

Consider the elevator dynamic model

\[
\left( J_1 + J_2 + r^2(m_1 + m_2) \right)\dot{\omega}
+(b_1 + b_2)\omega
= \tau + gr(m_1 - m_2),
\]

with output defined as the vertical velocity of the elevator load

\[
v_1 = r\omega.
\]

Using the same system parameters as in the balanced elevator case, determine the **open-loop motor torque** required so that the elevator velocity converges to a desired steady-state value

\[
\bar{v}_1 = 2\;\mathrm{m/s}
\]

as time \( t \to \infty \).

Analyze the time response of the system for different initial velocities and describe the qualitative behavior.

## Subproblems

1. Determine the desired steady-state angular velocity.
2. Derive the steady-state torque required to maintain this velocity.
3. Compute the numerical value of the required motor torque.
4. Derive the complete time-domain solution for \( v_1(t) \).
5. Describe the response for different initial conditions:
   - \( v_1(0) = 0 \)
   - \( v_1(0) = 1\;\mathrm{m/s} \)
   - \( v_1(0) = -1\;\mathrm{m/s} \)
6. Explain why the required torque is relatively small.

## Additional Information

- The elevator is perfectly balanced: \( m_1 = m_2 \).
- The motor torque is constant (open-loop).
- Gravity produces no net steady disturbance.
- Only viscous friction is present.
- The system is linear and time-invariant.

## Constraints

- Use analytical steady-state analysis.
- Clearly distinguish transient and steady-state behavior.
- Express all results in physically meaningful terms.
- Numerical substitution must be shown explicitly.
