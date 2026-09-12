# Problem

## Problem Description
 with a controller

\[
\tau = {K}_{\mathrm{i}}\left( {{\bar{x}}_{1} - {x}_{1}}\right),
\]

where

\[
{x}_{1}\left( t\right) = {x}_{1}\left( 0\right) + \int_{0}^{t}{v}_{1}\left( \tau \right)\, d\tau
\]

and the position reference

\[
{\bar{x}}_{1}\left( t\right) = {\bar{x}}_{1} = 10\,\mathrm{m}, \quad t \geq 0 .
\]

## Subproblems
1. Explain how changing the reference from velocity to position modifies the control objective.
2. Derive the modified plant transfer function from torque \( \tau \) to position \( x_1 \).
3. Write the controller transfer function and explain its structure.
4. Derive the closed-loop sensitivity function.
5. Determine the condition on the gain \( K \) for internal stability.
6. Analyze whether the closed-loop system can asymptotically track a constant position reference.
7. Describe the qualitative features of the closed-loop position response.

## Additional Information
- The parameters \( \alpha \) and \( \beta \) are the same as those defined in P4.23.
- The system is assumed to be linear and time-invariant.
- Only proportional feedback on position is considered.
- Initial conditions are assumed to be zero.

## Constraints
- Use Laplace-domain analysis.
- Stability must be justified by pole locations.
- Tracking performance should be explained using system type arguments.
- No additional dynamics may be added to the controller.
