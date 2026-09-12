# Problem

## Problem Description

 that the rotor torque is

\[
\tau  = {K}_{\mathrm{t}}{i}_{\mathrm{a}}
\]

The armature current, \( {i}_{\mathrm{a}} \), is related to the armature voltage, \( {v}_{\mathrm{a}} \), and the rotor angular velocity, \( \omega \), through

\[
{v}_{\mathrm{a}} = {R}_{\mathrm{a}}{i}_{\mathrm{a}} + {K}_{\mathrm{e}}\omega .
\]

Show that

\[
\frac{T\left( s\right) }{{V}_{\mathrm{a}}\left( s\right) } = \frac{{K}_{\mathrm{t}}}{{R}_{\mathrm{a}}}\frac{\left( s + b/J\right) }{\left( s + b/J + {K}_{\mathrm{e}}{K}_{\mathrm{t}}/\left( {R}_{\mathrm{a}}J\right) \right) }
\]

is the transfer-function from \( {v}_{\mathrm{a}} \) to \( \tau \).

## Subproblems

1. Express the relationship between armature current and torque.
2. Rewrite the electrical equation relating armature voltage, current, and angular velocity.
3. Eliminate the armature current to express torque in terms of voltage and angular velocity.
4. Take Laplace transforms of the governing equations.
5. Substitute the previously derived transfer function between angular velocity and armature voltage.
6. Derive the transfer function from armature voltage to torque.
7. Identify the zero and pole of the resulting transfer function.
8. Interpret the physical meaning of the numerator and denominator dynamics.

## Additional Information

- The DC motor model neglects armature inductance.
- Mechanical friction is modeled as viscous damping.
- The system is assumed to be linear and time-invariant.
- All initial conditions are assumed to be zero.
- The transfer function between angular velocity and voltage has been derived previously.

## Constraints

- Algebraic manipulation must be consistent with Laplace-domain analysis.
- Physical parameters should retain their original units.
- Intermediate substitutions should be clearly justified.
- Final expressions must be written in standard transfer-function form.
