# Solution

## Method

Because \( \left| {{p}_{\varepsilon }\left( \tau \right) }\right|  = {p}_{\varepsilon }\left( \tau \right) \) ,

\[
\mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}{\int }_{{0}^{ - }}^{\infty }\left| {{p}_{\varepsilon }\left( \tau \right) }\right| {d\tau } = 1,
\]


## Teaching Points
1. **Positivity of Basis Functions**: In signal analysis, standard pulse approximations for the Dirac Delta function are typically non-negative, meaning their absolute integral is equal to their standard integral.
2. **Unit Area Constraint**: The core definition of a "unit" pulse is that its total area (the integral) remains $1$ even as the width narrows and height increases.
3. **Absolute Integrability**: The fact that the limit of the absolute integral is finite (and specifically 1) indicates that the pulse function remains "well-behaved" in the sense of $L^1$ norm during the limiting process.
4. **Physical Interpretation**: In systems and control, this represents a unit-strength stimulus, where the total "effort" or "energy" (in terms of area) is preserved during the transition to an ideal impulse.