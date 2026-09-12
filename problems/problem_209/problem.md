# Problem

## Problem Description

You have shown that the ordinary differential equations

\[
{m}_{1}{\ddot{x}}_{1} + \left( {{b}_{1} + {b}_{2}}\right) {\dot{x}}_{1} + \left( {{k}_{1} + {k}_{2}}\right) {x}_{1} - {b}_{2}{\dot{x}}_{2} - {k}_{2}{x}_{2} = {f}_{1}
\]

\[
{m}_{2}{\ddot{x}}_{2} + {b}_{2}\left( {{\dot{x}}_{2} - {\dot{x}}_{1}}\right)  + {k}_{2}\left( {{x}_{2} - {x}_{1}}\right)  = {f}_{2}
\]

constitute a simplified description of the motion of the mass-spring-damper system in Fig. 2.20(b), where \( {x}_{1} \) and \( {x}_{2} \) are displacements, and \( {f}_{1} \) and \( {f}_{2} \) are forces applied on the masses \( {m}_{1} \) and \( {m}_{2} \). Let the force, \( {f}_{2} \), be the control input and the displacement, \( {x}_{2} \), be the measured output. Let \( {m}_{1} = {m}_{2} = 1\mathrm{\;{kg}} \), \( {b}_{1} = {b}_{2} = {0.1}\mathrm{\;{kg}}/\mathrm{s} \), \( {k}_{1} = 1\mathrm{\;N}/\mathrm{m} \), and \( {k}_{2} = 2\mathrm{\;N}/\mathrm{m} \). Use the root-locus method to design a dynamic feedback controller that uses \( {f}_{2} \) as control input and \( {x}_{2} \) as the measured output and that can regulate the position, \( {x}_{2} \), at zero for any constant possible value of force \( {f}_{1} \).

Hint: Treat the force \( {f}_{1} \) as a disturbance.

## Subproblems

1. Write the coupled equations of motion in state-space form.
2. Identify the system states, control input, measured output, and disturbance input.
3. Derive the transfer functions from \( f_{1} \) and \( f_{2} \) to the output \( x_{2} \).
4. Analyze the open-loop pole structure of the system.
5. Explain why a controller with integral action is required.
6. Use root-locus arguments to justify the chosen controller structure.
7. Discuss stability and oscillatory behavior of the closed-loop system.

## Additional Information

- The disturbance force \( f_{1} \) is constant but unknown.
- Only the displacement \( x_{2} \) is available for feedback.
- All system parameters are known and fixed.
- Root-locus analysis may be qualitative.

## Constraints

- The controller must be linear, causal, and time-invariant.
- Only dynamic output feedback is allowed.
- Zero steady-state error to constant disturbances is required.
- Closed-loop internal stability must be guaranteed.
