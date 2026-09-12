# Problem

## Problem Description

You have shown that the ordinary differential equation

\[
J\dot{\omega } + \left( {b + \frac{{K}_{\mathrm{e}}{K}_{\mathrm{t}}}{{R}_{\mathrm{a}}}}\right) \omega  = \frac{{K}_{\mathrm{t}}}{{R}_{\mathrm{a}}}{v}_{\mathrm{a}}
\]

is a simplified description of the motion of the rotor of the DC motor in Fig. 2.24, where \( \omega \) is the rotor angular velocity. Let  
\( J = {227} \times  {10}^{-6}\mathrm{\;{kg}}{\mathrm{\;m}}^{2} \),  
\( {K}_{\mathrm{t}} = {0.02}\mathrm{\;N}\mathrm{\;m}/\mathrm{A} \),  
\( {K}_{\mathrm{e}} = {0.02}\mathrm{\;V}\mathrm{\;s}/\mathrm{{rad}} \),  
\( b = {289.4} \times  {10}^{-6}\mathrm{\;{kg}}{\mathrm{\;m}}^{2}/\mathrm{s} \),  
and \( {R}_{\mathrm{a}} = {7\Omega } \).

Design a feedback controller

\[
{v}_{\mathrm{a}} = K\left( {\overline{\omega } - \omega }\right),
\]

and select \( K \) such that the closed-loop system is internally stable.  
Can the closed-loop system asymptotically track a constant-angular-velocity reference  
\( \overline{\omega }\left( t\right)  = \overline{\omega }, t \geq  0 \) ?

Assuming zero as the initial condition, sketch or use MATLAB to plot the closed-loop response when  
\( \overline{\omega } = {900}\mathrm{{RPM}} \).

## Subproblems

1. Rewrite the DC motor dynamics in normalized first-order state-space or differential equation form.
2. Identify the system parameters \( \alpha \) and \( \beta \) in terms of the physical constants.
3. Derive the open-loop transfer function from armature voltage to angular velocity.
4. Formulate the closed-loop system using proportional feedback control.
5. Determine the condition on the gain \( K \) for internal stability.
6. Analyze whether the closed-loop system can asymptotically track a constant reference input.
7. Convert the reference speed from RPM to rad/s.
8. Describe the qualitative features of the closed-loop time response, including steady-state error.

## Additional Information

- The DC motor is assumed to be linear and time-invariant.
- Electrical dynamics of the armature circuit are neglected.
- The feedback controller is purely proportional with no integral action.
- Internal stability refers to boundedness of all internal signals.

## Constraints

- All derivations must be consistent with classical linear control theory.
- Stability analysis should be based on pole locations of the closed-loop transfer function.
- Reference tracking performance must be justified analytically.
- Units should be handled consistently throughout the analysis.
