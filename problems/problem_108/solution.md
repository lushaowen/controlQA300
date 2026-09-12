# Solution

## Method
Assuming zero initial conditions, in the case of a constant torque, \( \tau \left( t\right) \) , and constant gravitational torque, \( w\left( t\right) \) , we set

\[
T\left( s\right)  = \frac{\widetilde{\tau }}{s},\;W\left( s\right)  = \frac{\widetilde{w}}{s},\;\widetilde{w} = {gr}\left( {{m}_{1} - {m}_{2}}\right) ,
\]

and calculate

\[
{V}_{1}\left( s\right)  = {G}_{\tau }\left( s\right) T\left( s\right)  + {G}_{w}\left( s\right) W\left( s\right)  = G\left( s\right) \left( {T\left( s\right)  + W\left( s\right) }\right)  = \frac{\beta }{s + \alpha }\frac{\widetilde{\tau } + \widetilde{w}}{s},
\]

where \( \alpha \) and \( \beta \) are as in P3.62. Expanding in partial fractions as in (C.1):

\[
{V}_{1}\left( s\right)  = \frac{\beta \left( {\widetilde{\tau } + \widetilde{w}}\right) }{\alpha }\left( {\frac{1}{s} - \frac{1}{s + \alpha }}\right)
\]

and from (C.2):

\[
{v}_{1}\left( t\right)  = \frac{r\left( {\widetilde{\tau } + \widetilde{w}}\right) }{{b}_{1} + {b}_{2}}\left( {1 - {e}^{-{\alpha t}}}\right) ,\;t \geq  0.
\]

The transient and steady-state components are

\[
{v}_{1\mathrm{{tr}}}\left( t\right)  =  - \frac{r\left( {\widetilde{\tau } + \widetilde{w}}\right) }{{b}_{1} + {b}_{2}}{e}^{\lambda t},\;{v}_{1\mathrm{{ss}}}\left( t\right)  = \frac{r\left( {\widetilde{\tau } + \widetilde{w}}\right) }{{b}_{1} + {b}_{2}}.
\]

## Teaching Points
1. Response of first-order systems to step (constant) inputs.
2. Superposition of multiple constant inputs in linear systems.
3. Use of partial fraction expansion to simplify inverse Laplace transforms.
4. Interpretation of exponential terms as transient behavior.
5. Identification of steady-state velocity from system parameters.
6. Physical meaning of damping in limiting long-term velocity.
