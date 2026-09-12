# Problem

## Problem Description

You showed  that the torque of a DC motor, \( \tau \) , is related to the armature voltage, \( {v}_{\mathrm{a}} \) , through the transfer-function

\[
\frac{T\left( s\right) }{{V}_{\mathrm{a}}\left( s\right) } = \frac{{K}_{\mathrm{t}}}{{R}_{\mathrm{a}}}\frac{\left( s + b/J\right) }{s + b/J + {K}_{\mathrm{e}}{K}_{\mathrm{t}}/\left( {{R}_{\mathrm{a}}J}\right) }.
\]

Use the data from P7.29 and Bode and Nyquist plots to design a controller that uses the voltage \( {v}_{\mathrm{a}} \) as the control input and the torque \( \tau \) as the measured output so that the closed-loop system is capable of asymptotically tracking a constant reference input torque \( \overline{\tau }\left( t\right)  = \overline{\tau }, t \geq  0 \) . Calculate the corresponding gain and phase margins.

## Subproblems

1. Substitute the numerical parameters into the torque-to-voltage transfer function.
2. Identify the poles and zeros of the resulting plant model.
3. Determine the system type and its steady-state tracking capability.
4. Explain why integral action is required for asymptotic tracking of a constant torque reference.
5. Propose a suitable dynamic controller structure.
6. Form the loop transfer function for the closed-loop system.
7. Use Bode plots to determine gain and phase margins.
8. Apply the Nyquist stability criterion to verify closed-loop stability.
9. Interpret the robustness properties implied by the stability margins.

## Additional Information

- Armature inductance effects are neglected.
- The DC motor parameters are assumed to be constant.
- The system is linear and time-invariant.
- Torque is assumed to be directly measurable.
- Classical frequency-domain design methods apply.

## Constraints

- Controller design must be based on Bode and Nyquist analysis.
- Asymptotic tracking of a constant reference torque is required.
- Stability margins must be explicitly calculated.
- Explanations must be consistent with classical control theory.
- No time-domain tuning methods are to be used.
