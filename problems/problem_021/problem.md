# Problem: First-Order Dynamic Model and Velocity Response of an Elevator System

## Problem Description

Based on the dynamic model of an elevator system derived previously, consider the simplified equation of motion

\[
\left( J_1 + J_2 + r^2(m_1 + m_2) \right)\dot{\omega}
+(b_1 + b_2)\omega
= \tau + gr(m_1 - m_2),
\]

where \( \omega \) is the angular velocity of the pulley, and the vertical velocity of the elevator load is

\[
v_1 = r\omega.
\]

Treat the elevator as a first-order dynamic system with:
- **Output:** vertical velocity \( v_1(t) \)
- **Inputs:** motor torque \( \tau \) and gravitational torque \( gr(m_1 - m_2) \)

Derive the corresponding first-order ordinary differential equation, solve it analytically, and analyze the velocity response for different initial conditions.

Use the following numerical values:

\[
\begin{aligned}
& g = 10\;\mathrm{m/s^2}, \quad \tau = 0\;\mathrm{N\,m}, \quad r = 1\;\mathrm{m}, \\
& m_1 = m_2 = 1000\;\mathrm{kg}, \\
& b_1 = b_2 = 120\;\mathrm{kg\,m^2/s}, \\
& J_1 = J_2 = 20\;\mathrm{kg\,m^2}.
\end{aligned}
\]

## Subproblems

1. Reduce the elevator dynamics to a first-order differential equation in \( \omega(t) \).
2. Express the system in standard first-order linear form.
3. Solve the differential equation analytically for zero motor torque.
4. Compute the numerical value of the system decay rate.
5. Express the solution in terms of the output velocity \( v_1(t) \).
6. Describe the responses for different initial velocities:
   - \( v_1(0) = 0 \)
   - \( v_1(0) = 1\;\mathrm{m/s} \)
   - \( v_1(0) = -1\;\mathrm{m/s} \)

## Additional Information

- The elevator load and counterweight are perfectly balanced.
- Gravity therefore produces no net steady torque.
- The system is linear and time-invariant.
- Only viscous damping is present.
- The analysis focuses on free response behavior.

## Constraints

- Use analytical solution methods.
- Clearly relate angular velocity to linear velocity.
- All numerical substitutions must be shown.
- Interpret results physically, not only mathematically.
