# Problem

## Problem Description

Consider the elevator velocity control system introduced in P2.18–P2.19 and controlled using the proportional feedback law

\[
\tau(t) = K\left(\bar{v}_1 - v_1(t)\right).
\]

the counterweight mass was equal to the elevator load, resulting in zero gravitational torque.

 assume the counterweight mass is reduced to

\[
m_2 = 800\;\mathrm{kg},
\]

while the elevator load remains \( m_1 = 1000\;\mathrm{kg} \). Treat the gravitational torque

\[
gr(m_1 - m_2)
\]

as a constant external disturbance acting on the system.

## Subproblems

1. Recalculate the proportional controller gain \( K \) to achieve the same closed-loop time constant.
2. Derive the closed-loop differential equation including the disturbance term.
3. Compute the resulting steady-state velocity error.
4. Compare the closed-loop and open-loop time constants.
5. Plot or sketch the closed-loop velocity response for different initial conditions.
6. Discuss the impact of gravitational disturbance on steady-state performance.
7. Compare the results with the disturbance-free case.

## Additional Information

- Use the same system parameters.
- Desired velocity: \( \bar{v}_1 = 2\;\mathrm{m/s} \).
- The controller is purely proportional.
- Gravity is constant and known.
- The disturbance is not compensated explicitly.

## Constraints

- The model must remain first-order.
- The disturbance must be treated as an external input.
- No integral action may be introduced.
- All conclusions must be supported analytically.
