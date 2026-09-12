# Problem

## Problem Description
Consider the one-quarter-car model. Show that

\[
{m}_{\mathrm{u}}\ddot{x} - {b}_{\mathrm{u}}\dot{z} - {k}_{\mathrm{u}}z = \left( {1 + {m}_{\mathrm{u}}/{m}_{\mathrm{s}}}\right) u
\]

\[
{m}_{\mathrm{u}}\ddot{z} + {b}_{\mathrm{u}}\dot{z} + {k}_{\mathrm{u}}z =  - u - {m}_{\mathrm{u}}\ddot{y}
\]

where

\[
u =  - \left( {{k}_{\mathrm{s}}x + {b}_{\mathrm{s}}\dot{x}}\right) ,
\]

can be interpreted as the output of a PD controller. Use this fact to using the root-locus method.

## Subproblems
1. Starting from the equations of motion in P6.24, derive the two given second-order differential equations involving \( x \) and \( z \).
2. Show explicitly how the control input \( u \) can be written as a proportional–derivative (PD) control law.
3. Interpret the physical meaning of the proportional and derivative terms in the context of a quarter-car suspension system.
4. Reformulate the system into a state-space realization suitable for control analysis.
5. Derive the transfer function from the control input \( u \) to the output displacement \( x \).
6. Apply the root-locus method to analyze how the PD controller parameters affect closed-loop pole locations.
7. Determine controller gains that satisfy specified natural frequency and damping ratio requirements.

## Additional Information
- The one-quarter-car model represents vertical dynamics of a vehicle suspension with sprung and unsprung masses.
- Parameters \( m_s, m_u, k_s, b_s, k_u, b_u \) denote masses, stiffnesses, and damping coefficients.
- Road disturbance is represented by the input \( y(t) \).
- Assume linear behavior of springs and dampers.
- Root-locus analysis follows standard continuous-time control theory.

## Constraints
- Algebraic manipulation steps must be consistent with Newton’s laws.
- Controller interpretation should be consistent with classical PD control definitions.
- Root-locus plots should be based on the open-loop transfer function.
- Physical interpretations should accompany mathematical derivations.
