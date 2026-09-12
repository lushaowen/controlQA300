# Problem

## Problem Description
 with a controller

\[
{v}_{\mathrm{a}}\left( t\right)  = {K}_{\mathrm{i}}{\int }_{0}^{t}e\left( \tau \right) {d\tau },\;e = \overline{\omega } - \omega .
\]

## Subproblems

1. Write the transfer function of the DC motor relating armature voltage to angular velocity.
2. Express the integral controller in the Laplace domain.
3. Derive the closed-loop sensitivity transfer function.
4. Compute the closed-loop characteristic equation.
5. Determine the poles of the closed-loop system as a function of \( K_i \).
6. Identify the conditions on \( K_i \) that guarantee internal stability.
7. Analyze whether the closed-loop system can asymptotically track a constant reference signal.
8. Interpret the effect of integral control on steady-state tracking error.
9. Describe the qualitative shape of the closed-loop step response.

## Additional Information

- The DC motor model is assumed to be linear and time-invariant.
- The plant dynamics are first order.
- The controller consists purely of integral action.
- Zero initial conditions are assumed for both the plant and the controller.
- Reference input is a constant angular velocity.

## Constraints

- Stability analysis must be performed using pole locations.
- Integral control must be represented explicitly in the Laplace domain.
- Tracking properties should be justified using system type arguments.
- Units must remain consistent throughout the analysis.
