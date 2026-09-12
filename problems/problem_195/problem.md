# Problem

## Problem Description

Show that the step response of an underdamped second-order system with transfer-function

\[
G\left( s\right)  = \frac{{\omega }_{\mathrm{n}}^{2}}{{s}^{2} + {2\zeta }{\omega }_{\mathrm{n}}s + {\omega }_{\mathrm{n}}^{2}},\;{\omega }_{\mathrm{n}} > 0,
\]

is

\[
y\left( t\right)  = 1 - \frac{{e}^{-\zeta {\omega }_{\mathrm{n}}t}}{\sqrt{1 - {\zeta }^{2}}}\sin \left( {{\omega }_{\mathrm{d}}t + \pi /2 - {\phi }_{\mathrm{d}}}\right) ,
\]

where

\[
{\omega }_{\mathrm{d}} = {\omega }_{\mathrm{n}}\sqrt{1 - {\zeta }^{2}},\;{\phi }_{\mathrm{d}} = {\tan }^{-1}\left( \frac{\zeta }{\sqrt{1 - {\zeta }^{2}}}\right) ,
\]

for \( t \geq  0,0 < \zeta  < 1 \) .

## Subproblems

1. Write the Laplace transform of the unit step input and determine the expression for \( Y(s) \).
2. Factor the denominator of \( G(s) \) and identify the system poles.
3. Perform a partial fraction expansion of \( Y(s) \).
4. Apply the inverse Laplace transform to obtain the time-domain response.
5. Express the oscillatory terms in sinusoidal form with amplitude and phase.
6. Identify the damping-dependent frequency and phase shift.

## Additional Information

- The system is assumed to be linear, time-invariant, and initially at rest.
- The damping ratio satisfies \( 0 < \zeta < 1 \), corresponding to the underdamped case.
- Complex conjugate poles lead to exponentially decaying oscillations.
- Residue calculus or standard Laplace transform tables may be used.

## Constraints

- The derivation must explicitly show intermediate algebraic steps.
- Complex exponentials must be converted into real-valued sinusoidal expressions.
- The final result should clearly identify amplitude, frequency, phase, and decay rate.
- The solution must be valid for all \( t \geq 0 \).
