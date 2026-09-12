# Problem

## Problem Description
 with a controller

\[
\tau = {K}_{\mathrm{i}}\left( {{\overline{\theta }}_{2} - {\theta }_{2}}\right),
\]

where

\[
{\theta }_{2}\left( t\right) = {\theta }_{2}\left( 0\right) + \int_{0}^{t}{\omega }_{2}\left( \sigma \right)\, d\sigma,
\]

and the angular reference

\[
{\overline{\theta }}_{2}\left( t\right) = {\overline{\theta }}_{2} = \pi , \quad t \geq 0 .
\]

## Subproblems
1. Explain how the change from angular velocity reference to angular position reference affects the control structure.
2. Derive the modified plant transfer function from torque \( \tau \) to angular position \( \theta_2 \).
3. Formulate the closed-loop transfer function under proportional position feedback.
4. Determine the closed-loop poles as a function of the controller gain \( K_i \).
5. Identify the conditions on \( K_i \) that ensure internal stability.
6. Analyze whether the closed-loop system can asymptotically track a constant angular reference.

## Additional Information
- The parameters \( \alpha \) and \( \beta \) are identical to those defined in P4.20.
- The system is assumed to be linear and time-invariant.
- The reference signal is a constant angular position.
- Initial conditions are assumed to be zero unless otherwise stated.

## Constraints
- Analysis should be performed using Laplace-domain methods.
- Stability must be justified using pole locations.
- Tracking performance should be discussed using system type arguments.
- Only proportional control on angular position is allowed.
