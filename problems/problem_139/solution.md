# Solution

## Method
We have

\[
G\left( s\right) = \frac{{\Omega }_{2}\left( s\right) }{T\left( s\right) } = \frac{\beta }{s + \alpha },
\]

where

\[
\beta = \frac{{r}_{1}{r}_{2}}{{J}_{1}{r}_{2}^{2} + {J}_{2}{r}_{1}^{2}},\;
\alpha = \frac{{b}_{1}{r}_{2}^{2} + {b}_{2}{r}_{1}^{2}}{{J}_{1}{r}_{2}^{2} + {J}_{2}{r}_{1}^{2}}.
\]

Further, \( K\left( s\right) = K \), such that

\[
S\left( s\right) = \frac{1}{1 + G\left( s\right) K\left( s\right) }
= \frac{s + \alpha }{s + \alpha + {\beta K}},
\]

which renders the closed-loop system internally stable for any

\[
K > -\frac{\alpha}{\beta}.
\]

Given that neither the controller nor the plant has a pole at the origin, the closed-loop system is a type-0 system and therefore does **not** achieve asymptotic tracking of a constant reference input.

The closed-loop response to a reference input  
\( {\overline{\omega }}_{2} = 4.5\,\mathrm{rad/s} \) with \( K = 1 \) exhibits a stable first-order response with a nonzero steady-state tracking error.

Note the nonzero tracking error.
![](images\bo_d5ctcr3ef24c73bj2om0_69_446_1470_779_258_0.jpg)
## Teaching Points
1. Modeling of rotational mechanical systems using equivalent inertia and damping.
2. Interpretation of belt-driven systems and velocity ratios.
3. Use of proportional feedback and its effect on stability.
4. Relationship between system type and steady-state tracking error.
5. Importance of integrators for zero steady-state error to step references.
6. Physical interpretation of closed-loop pole placement.
