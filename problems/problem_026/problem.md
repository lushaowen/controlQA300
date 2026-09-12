# Problem

## Problem Description

Consider the closed-loop elevator velocity control system developed, where a proportional feedback controller

\[
\tau(t) = K\left(\bar{v}_1 - v_1(t)\right)
\]

is used to regulate the elevator velocity. The closed-loop dynamics are governed by

\[
\left( J_1 + J_2 + r^2(m_1 + m_2) \right)\dot{\omega}
+(b_1 + b_2 + rK)\omega
= rK\bar{\omega} + gr(m_1 - m_2).
\]

the controller gain was selected such that the closed-loop time constant was approximately \(5\;\mathrm{s}\).

In this problem, repeat the analysis but instead choose the controller gain so that the closed-loop time constant is approximately

\[
\tau_{\mathrm{cl}} = 0.5\;\mathrm{s}.
\]

## Subproblems

1. Compute the proportional gain \( K \) required to achieve a closed-loop time constant of \(0.5\;\mathrm{s}\).
2. Compare the closed-loop and open-loop time constants.
3. Compute the resulting steady-state velocity error.
4. Plot or sketch the closed-loop response for different initial velocities.
5. Discuss the qualitative effect of increasing the feedback gain.
6. Identify potential practical or physical limitations of this high-gain solution.
7. Compare the response with that obtained in P2.23.

## Additional Information

- Use the same system parameters as in P2.19.
- The desired steady-state velocity is \( \bar{v}_1 = 2\;\mathrm{m/s} \).
- The controller remains purely proportional.
- Assume ideal sensing and actuation.

## Constraints

- The system must remain first-order.
- Controller saturation effects should be discussed qualitatively.
- Physical feasibility must be considered.
- Results must be compared with lower-gain designs.
