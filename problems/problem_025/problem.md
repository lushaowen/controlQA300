# Problem: Closed-Loop Velocity Control of an Elevator Using Proportional Feedback

## Problem Description

Consider the elevator system introduced, whose dynamics are described by

\[
\left( J_1 + J_2 + r^2(m_1 + m_2) \right)\dot{\omega}
+(b_1 + b_2)\omega
= \tau + gr(m_1 - m_2),
\]

with the elevator load velocity defined as

\[
v_1 = r\omega.
\]

A proportional feedback controller is introduced to regulate the elevator velocity:

\[
\tau(t) = K\left(\bar{v}_1 - v_1(t)\right),
\]

where the desired vertical velocity is

\[
\bar{v}_1 = 2\;\mathrm{m/s}.
\]

 analyze the closed-loop behavior of the elevator.

## Subproblems

1. Derive the closed-loop differential equation of the elevator system.
2. Solve the resulting first-order differential equation.
3. Express the closed-loop time constant in terms of system parameters and gain \( K \).
4. Choose a controller gain such that the time constant is approximately \( 5\;\mathrm{s} \).
5. Compare the closed-loop time constant with the open-loop value.
6. Compute the closed-loop steady-state velocity error.
7. Analyze the effect of proportional feedback on disturbance rejection.
8. Plot the closed-loop velocity response for different initial velocities.
9. Compare the closed-loop response with the open-loop response from P2.22.

## Additional Information

- Use numerical data from P2.19.
- Gravity acts as a constant disturbance.
- The controller is purely proportional.
- No integral or derivative action is included.
- The system is linear and time-invariant.

## Constraints

- All steps must be analytically justified.
- Physical interpretation is required.
- Time constants and steady-state errors must be clearly distinguished.
- Responses should be consistent with first-order system behavior.
