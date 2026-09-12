# Problem

## Problem Description
Consider the DC motor with the same physical parameters as. Design a feedback controller

\[
{v}_{\mathrm{a}} = K\left( {\overline{\tau } - \tau }\right) ,
\]

and select \( K \) such that the closed-loop system is internally stable. Can the closed-loop system asymptotically track a constant-torque reference \( \overline{\tau }\left( t\right)  = \overline{\tau }, t \geq  0 \) ? Assuming zeros as the initial conditions, sketch or use MATLAB to plot the closed-loop response when \( \overline{\tau } = {0.5}\mathrm{\;N}\mathrm{\;m} \) .

## Subproblems
1. Write down the transfer function of the DC motor torque dynamics.
2. Derive the closed-loop sensitivity function under proportional feedback.
3. Determine the conditions on the gain \( K \) for internal stability.
4. Analyze whether the closed-loop system can asymptotically track a constant torque reference.
5. Explain the role of system type and pole locations in steady-state tracking.
6. Simulate or sketch the closed-loop response for a constant torque reference input.

## Additional Information
- The DC motor model is linear and time-invariant.
- All physical parameters are strictly positive.
- The feedback controller is purely proportional.
- Initial conditions are assumed to be zero.
- Stability should be assessed using pole locations of the closed-loop transfer function.

## Constraints
- No integral or derivative control actions are allowed.
- Analysis must be carried out using transfer function methods.
- Stability conclusions must be supported by mathematical reasoning.
- Simulation results should be consistent with theoretical predictions.
