# Problem

## Problem Description
You have shown that the ordinary differential equation

\[
\left( {{J}_{1}{r}_{2}^{2} + {J}_{2}{r}_{1}^{2}}\right) {\dot{\omega }}_{1} + \left( {{b}_{1}{r}_{2}^{2} + {b}_{2}{r}_{1}^{2}}\right) {\omega }_{1} = {r}_{2}^{2}\tau ,\;{\omega }_{2} = \left( {{r}_{1}/{r}_{2}}\right) {\omega }_{1}
\]

is a simplified description of the motion of a rotating machine driven by a belt without slip as in Fig. 2.18(a), where \( {\omega }_{1} \) is the angular velocity of the driving shaft and \( {\omega }_{2} \) is the machine’s angular velocity. Let  
\( {r}_{1} = {25}\mathrm{\;{mm}}, {r}_{2} = {500}\mathrm{\;{mm}}, {b}_{1} = {0.01}\mathrm{\;{kg}}{\mathrm{\;m}}^{2}/\mathrm{s} \),  
\( {b}_{2} = {0.1}\mathrm{\;{kg}}{\mathrm{\;m}}^{2}/\mathrm{s}, {J}_{1} = {0.0031}\mathrm{\;{kg}}{\mathrm{\;m}}^{2} \),  
and \( {J}_{2} = {25}\mathrm{\;{kg}}{\mathrm{\;m}}^{2} \).

Design a feedback controller

\[
\tau = K\left( {{\overline{\omega }}_{2} - {\omega }_{2}}\right),
\]

and select \( K \) such that the closed-loop system is internally stable. Can the closed-loop system asymptotically track a constant reference  
\( {\overline{\omega }}_{2}\left( t\right) = {\overline{\omega }}_{2}, t \geq 0 \) ?  
Assuming zero as the initial condition, sketch or use MATLAB to plot the closed-loop response when  
\( {\overline{\omega }}_{2} = {4.5}\mathrm{{rad}}/\mathrm{s} \).

## Subproblems
1. Derive the transfer function from the applied torque \( \tau \) to the output angular velocity \( \omega_2 \).
2. Express the system parameters \( \alpha \) and \( \beta \) in terms of the physical constants.
3. Formulate the closed-loop transfer function under proportional feedback control.
4. Determine the condition on the gain \( K \) that guarantees internal stability.
5. Analyze whether the closed-loop system can asymptotically track a constant reference input.
6. Describe the qualitative behavior of the closed-loop step response for a constant reference input.

## Additional Information
- The belt is assumed to be rigid and without slip.
- All parameters are constant and positive.
- The system is modeled as a linear time-invariant (LTI) system.
- Only proportional feedback control is considered.

## Constraints
- Use Laplace transform techniques for analysis.
- Stability should be discussed in terms of pole locations.
- Tracking performance should be justified using system type arguments.
- Initial conditions are assumed to be zero.
