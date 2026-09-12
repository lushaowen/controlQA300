# Problem

## Problem Description
You have shown that the torque of a DC motor, \( \tau \) , is related to the armature voltage, \( {v}_{\mathrm{a}} \) , through the transfer-function

\[
\frac{T\left( s\right) }{{V}_{\mathrm{a}}\left( s\right) } = \frac{{K}_{\mathrm{t}}}{{R}_{\mathrm{a}}}\frac{\left( s + b/J\right) }{s + b/J + {K}_{\mathrm{e}}{K}_{\mathrm{t}}/\left( {{R}_{\mathrm{a}}J}\right) }.
\]

Use the data from P6.30 and the root-locus method to design a controller that uses the voltage \( {v}_{\mathrm{a}} \) as the control input and the torque \( \tau \) as the measured output so that the closed-loop system is capable of asymptotically tracking a constant reference input torque

\[
\overline{\tau }\left( t\right)  = \overline{\tau }, \quad t \geq  0 .
\]

## Subproblems
1. Rewrite the given transfer function in a normalized pole–zero form.
2. Identify the locations of the open-loop pole and zero.
3. Determine the system type with respect to constant torque reference tracking.
4. Explain why an additional pole at the origin is required.
5. Propose a suitable dynamic controller to increase the system type.
6. Construct the loop transfer function of the compensated system.
7. Analyze the root-locus and discuss stability for positive controller gains.
8. Comment on the effect of the zero on transient response.

## Additional Information
- The DC motor model neglects armature inductance.
- Torque is directly proportional to armature current.
- Constant reference tracking implies zero steady-state error.
- Root-locus analysis is performed in the continuous-time domain.
- Parameter values are taken directly from P6.30.

## Constraints
- Controller design must use classic
