# Solution

## Method

Assuming that \( {m}_{1} = {m}_{2} \), we get the following transfer function between \( \tau \) and \( {v}_{1} \),

\[
\frac{{V}_{1}\left( s\right) }{\mathrm{T}\left( s\right) }
= \frac{r}
{s\left( {{J}_{1} + {J}_{2} + {r}^{2}\left( {{m}_{1} + {m}_{2}}\right) }\right)
+\left( {{b}_{1} + {b}_{2}}\right) }.
\]

Assuming zero initial conditions, we also have

\[
{X}_{1}\left( s\right) = \frac{{V}_{1}\left( s\right) }{s},
\]

which gives us the following open-loop transfer function,

\[
G\left( s\right)
= \frac{r}
{{s}^{2}\left( {{J}_{1} + {J}_{2} + {r}^{2}\left( {{m}_{1} + {m}_{2}}\right) }\right)
+s\left( {{b}_{1} + {b}_{2}}\right) }.
\]

With the physical values, we get the following

\[
G\left( s\right) = \frac{\beta }{s\left( {s + \alpha }\right) },
\]

where

\[
\alpha
= \frac{{b}_{1} + {b}_{2}}{{J}_{1} + {J}_{2} + {r}^{2}\left( {{m}_{1} + {m}_{2}}\right) },
\quad
\beta
= \frac{r}{{J}_{1} + {J}_{2} + {r}^{2}\left( {{m}_{1} + {m}_{2}}\right) }.
\]

This transfer function has poles at \( s = 0 \) and \( s = -0.1176 \).
We plot the Nyquist plot for \( G\left( s\right) \) in Figure G.10.
As indicated, no point on the negative real axis is encircled.
Given that the loop transfer function has no poles in the right-hand plane,
this guarantees asymptotic stability for any \( K\left( s\right) = K > 0 \).

Asymptotic tracking follows from the pole at \( s = 0 \) in the open-loop transfer function.
Selecting \( K = 1 \), we get a gain margin of infinity and a phase margin of 88 degrees.

## Teaching Points

1. Modeling of electromechanical systems with coupled rotational and translational dynamics
2. Effect of mass symmetry on gravitational disturbance cancellation
3. Interpretation of integrators in open-loop systems for tracking
4. Use of Bode plots to assess robustness
5. Application of the Nyquist criterion for unconditional stability
6. Relationship between pole locations and steady-state tracking
7. Interpretation of gain and phase margins in physical systems
