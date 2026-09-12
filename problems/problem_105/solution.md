# Solution

## Method
Assuming zero initial conditions, in the case of a constant torque we set

\[
T\left( s\right)  = \frac{\widetilde{\tau }}{s}
\]

and calculate

\[
{\Theta }_{2}\left( s\right)  = H\left( s\right) T\left( s\right)  = \frac{\beta }{s\left( {s + \alpha }\right) }\frac{\widetilde{\tau }}{s},
\]

where \( \alpha \) and \( \beta \) are as in P3.54. Expanding in partial fractions:

\[
\frac{\beta }{{s}^{2}\left( {s + \alpha }\right) } = \frac{\beta }{{\alpha }^{2}}\left( {\frac{\alpha }{{s}^{2}} - \frac{1}{s} + \frac{1}{s + \alpha }}\right) \tag{C.5}
\]

from which

\[
{\mathcal{L}}^{-1}\left\{  {\frac{\beta }{{\alpha }^{2}}\left( {\frac{\alpha }{{s}^{2}} - \frac{1}{s} + \frac{1}{s + \alpha }}\right) }\right\}   = \frac{\beta }{{\alpha }^{2}}\left( {{\alpha t} - 1 + {e}^{-{\alpha t}}}\right) ,\;t \geq  0, \tag{C.6}
\]

and

\[
{\theta }_{2}\left( t\right)  = \frac{\left( {{r}_{1}/{r}_{2}}\right) \left( {{J}_{1} + {J}_{2}{\left( {r}_{1}/{r}_{2}\right) }^{2}}\right) \widetilde{\tau }}{{\left( {b}_{1} + {b}_{2}{\left( {r}_{1}/{r}_{2}\right) }^{2}\right) }^{2}}\left( {{\alpha t} - 1 + {e}^{-{\alpha t}}}\right) .
\]

The transient and steady-state components are

\[
{\theta }_{2\mathrm{{tr}}}\left( t\right)  = \frac{\left( {{r}_{1}/{r}_{2}}\right) \left( {{J}_{1} + {J}_{2}{\left( {r}_{1}/{r}_{2}\right) }^{2}}\right) \widetilde{\tau }}{{\left( {b}_{1} + {b}_{2}{\left( {r}_{1}/{r}_{2}\right) }^{2}\right) }^{2}}{e}^{-{\alpha t}},
\]

\[
{\theta }_{2\mathrm{\;{ss}}}\left( t\right)  = \frac{\left( {{r}_{1}/{r}_{2}}\right) \left( {{J}_{1} + {J}_{2}{\left( {r}_{1}/{r}_{2}\right) }^{2}}\right) \widetilde{\tau }}{{\left( {b}_{1} + {b}_{2}{\left( {r}_{1}/{r}_{2}\right) }^{2}\right) }^{2}}\left( {{\alpha t} - 1}\right) .
\]

## Teaching Points
1. Relationship between angular velocity and angular position via integration
2. Interpretation of repeated poles at the origin in mechanical systems
3. Identification of linearly growing steady-state responses
4. Physical meaning of transient exponential decay in damped systems
5. Distinction between bounded and unbounded steady-state behavior
6. Importance of system damping in rotational dynamics
