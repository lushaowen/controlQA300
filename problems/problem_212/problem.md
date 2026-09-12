# Problem

## Problem Description

Consider the one-quarter-car model from P6.24. If the tire stiffness is \( {k}_{\mathrm{u}} = \; {200},{000}\mathrm{\;N}/\mathrm{m} \) and the tire damping coefficient is negligible, i.e. \( {b}_{\mathrm{u}} = 0 \), use MATLAB to calculate the transfer-function from the road profile, \( y \), to the relative displacement \( x + z \) and select values of the spring stiffness, \( {k}_{\mathrm{s}} \), and shock absorber damping coefficient, \( {b}_{\mathrm{s}} \), for a car with \( 1/4 \) mass \( {m}_{\mathrm{s}} = {600}\mathrm{\;{kg}} \) and wheel mass \( {m}_{\mathrm{u}} = {40}\mathrm{\;{kg}} \) to have its dominant poles display a natural frequency \( {f}_{\mathrm{n}} = {2.5}\mathrm{\;{Hz}} \) and damping ratio \( \zeta = {0.08} \). Locate all the roots in the complex plane.

## Subproblems

1. Recall the one-quarter-car model dynamics from P6.24.
2. Define the relative displacement output \( x + z \).
3. Construct a state-space model that accounts for road acceleration input.
4. Derive the output equation relating the state to \( x + z \).
5. Obtain the transfer function from road profile \( y \) to output \( x + z \).
6. Select suitable values of \( k_s \) and \( b_s \) to meet dominant pole specifications.
7. Compute and interpret all closed-loop poles in the complex plane.

## Additional Information

- Tire damping is neglected.
- Road excitation enters through second derivatives.
- Only passive suspension elements are considered.
- MATLAB is used for numerical eigenvalue analysis.

## Constraints

- The model must remain linear and time-invariant.
- Parameter values must be physically realistic.
- Dominant poles must satisfy the given frequency and damping specifications.
- All system poles must lie in the open left-half plane.
