# Problem

## Problem Description
 with a controller

\[
{v}_{\mathrm{a}}\left( t\right)  = {K}_{\mathrm{i}}{\int }_{0}^{t}e\left( \tau \right) {d\tau },\;e = \overline{\tau } - \tau .
\]

## Subproblems
1. Write the transfer function of the integral controller in the Laplace domain.
2. Derive the closed-loop sensitivity function for the DC motor with integral feedback.
3. Determine the conditions on the integral gain \( K_i \) for internal stability.
4. Analyze the pole locations of the closed-loop system.
5. Explain why integral control guarantees asymptotic tracking of constant reference signals.
6. Sketch or simulate the closed-loop torque response to a constant reference input.

## Additional Information
- The DC motor model is linear and time-invariant.
- All physical parameters are strictly positive.
- The controller contains a single integrator.
- Initial conditions are assumed to be zero.
- Stability is determined by the location of the closed-loop poles.

## Constraints
- Only integral control action is allowed.
- Analysis must be performed using transfer functions.
- Stability conclusions must be justified mathematically.
- Tracking performance must be explained using system type arguments.
