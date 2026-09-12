# Solution

## Method
Assuming zero initial conditions, in the case of a constant torque we set

\[
T\left( s\right)  = \frac{\widetilde{\tau }}{s}
\]

and calculate

\[
{\Omega }_{2}\left( s\right)  = G\left( s\right) T\left( s\right)  = \frac{\beta }{s + \alpha }\frac{\widetilde{\tau }}{s},
\]

where \( \alpha \) and \( \beta \) are as in P3.54. Expanding in partial fractions as in (C.1):

\[
{\Omega }_{2}\left( s\right)  = G\left( s\right) T\left( s\right)  = \frac{\beta \widetilde{\tau }}{\alpha }\left( {\frac{1}{s} - \frac{1}{s + \alpha }}\right)
\]

and from (C.2):

\[
{\omega }_{2}\left( t\right)  = \frac{\left( {{r}_{1}/{r}_{2}}\right) \widetilde{\tau }}{{b}_{1} + {b}_{2}{\left( {r}_{1}/{r}_{2}\right) }^{2}}\left( {1 - {e}^{-{\alpha t}}}\right) ,\;t \geq  0.
\]

The transient and steady-state components are

\[
{\omega }_{2\mathrm{{tr}}}\left( t\right)  =  - \frac{\left( {{r}_{1}/{r}_{2}}\right) \widetilde{\tau }}{{b}_{1} + {b}_{2}{\left( {r}_{1}/{r}_{2}\right) }^{2}}{e}^{\lambda t},\;
{\omega }_{2\mathrm{{ss}}}\left( t\right)  = \frac{\left( {{r}_{1}/{r}_{2}}\right) \widetilde{\tau }}{{b}_{1} + {b}_{2}{\left( {r}_{1}/{r}_{2}\right) }^{2}}.
\]

## Teaching Points
1. Representation of constant inputs in the Laplace domain
2. Use of transfer functions to model mechanical rotational systems
3. Application of partial-fraction expansion for inverse Laplace transforms
4. Interpretation of exponential terms as transient responses
5. Identification of steady-state behavior from final-value expressions
6. Physical meaning of damping parameters in rotating machinery
