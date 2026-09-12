# Problem

## Problem Description
You have shown in P2.18 that the ordinary differential equation

\[
\left( {{J}_{1} + {J}_{2} + {r}^{2}\left( {{m}_{1} + {m}_{2}}\right) }\right) \dot{\omega }
+\left( {{b}_{1} + {b}_{2}}\right) \omega
= \tau + {gr}\left( {{m}_{1} - {m}_{2}}\right),
\quad
{v}_{1} = {r\omega},
\]

is a simplified description of the motion of the elevator in Fig. 2.18(b), where \( \omega \) is the angular velocity of the driving shaft and \( {v}_{1} \) is the elevator’s load linear velocity.

Let  
\( g = 10\,\mathrm{m/s^{2}}, r = 1\,\mathrm{m}, {m}_{1} = {m}_{2} = 1000\,\mathrm{kg}, \)  
\( {b}_{1} = {b}_{2} = 120\,\mathrm{kg\,m^{2}/s}, {J}_{1} = {J}_{2} = 20\,\mathrm{kg\,m^{2}} \).

Design a feedback controller

\[
\tau = K\left( {{\bar{v}}_{1} - {v}_{1}}\right),
\]

and select \( K \) such that the closed-loop system is internally stable.  
Can the closed-loop system asymptotically track a constant velocity reference

\[
{v}_{1}\left( t\right) = {\bar{v}}_{1}, \quad t \geq 0 ?
\]

Assuming zero as the initial condition, sketch or use MATLAB to plot the closed-loop response when  
\( {\bar{v}}_{1} = 3\,\mathrm{m/s} \).

## Subproblems
1. Derive the first-order differential equation governing the elevator velocity.
2. Define the parameters \( \alpha \), \( \beta \), and the disturbance term \( w \).
3. Determine the transfer function from torque input \( \tau \) to velocity output \( v_1 \).
4. Derive the sensitivity function under proportional feedback control.
5. Identify the condition on the gain \( K \) for internal stability.
6. Analyze whether constant velocity references can be asymptotically tracked.
7. Explain the influence of system parameters on the choice of controller gain.

## Additional Information
- The elevator masses are balanced (\( m_1 = m_2 \)).
- The gravitational disturbance term may vanish depending on mass symmetry.
- The system is modeled as linear and time-invariant.
- Only proportional velocity feedback is considered.

## Constraints
- Laplace-domain analysis should be used.
- Stability must be discussed using pole locations.
- Tracking performance should be analyzed using system type arguments.
- Initial conditions are assumed to be zero.
