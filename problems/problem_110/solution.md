# Solution

## Method
As 

\[
T\left( s\right)  = \frac{\widetilde{\tau }}{s},\;W\left( s\right)  = \frac{\widetilde{w}}{s},\;\widetilde{w} = {gr}\left( {{m}_{1} - {m}_{2}}\right) ,
\]

and calculate

\[
{X}_{1}\left( s\right)  = \frac{{V}_{1}\left( s\right) }{s} = \frac{G\left( s\right) }{s}\left( {T\left( s\right)  + W\left( s\right) }\right)  = \frac{\beta }{s\left( {s + \alpha }\right) }\frac{\widetilde{\tau } + \widetilde{w}}{s},
\]

where \( \alpha \) and \( \beta \) are as in P3.62. Expanding in partial fractions as in (C.5):

\[
{X}_{1}\left( s\right)  = \frac{\beta \left( {\widetilde{\tau } + \widetilde{w}}\right) }{{\alpha }^{2}}\left( {\frac{\alpha }{{s}^{2}} - \frac{1}{s} + \frac{1}{s + \alpha }}\right)
\]

and from (C.6):

\[
{x}_{1}\left( t\right)  = \frac{\beta \left( {\widetilde{\tau } + \widetilde{w}}\right) }{{\alpha }^{2}}\left( {{\alpha t} - 1 + {e}^{-{\alpha t}}}\right) ,\;t \geq  0.
\]

The transient and steady-state components are

\[
{x}_{1\mathrm{{tr}}}\left( t\right)  = \frac{\beta \left( {\widetilde{\tau } + \widetilde{w}}\right) }{{\alpha }^{2}}{e}^{-{\alpha t}},
\]

\[
{x}_{1\mathrm{\;{ss}}}\left( t\right)  = \frac{\beta \left( {\widetilde{\tau } + \widetilde{w}}\right) }{{\alpha }^{2}}\left( {{\alpha t} - 1}\right) .
\]

## Teaching Points
1. Relationship between velocity and position through time integration.
2. Effect of constant inputs on position growth in first-order systems.
3. Use of repeated poles in Laplace-domain analysis.
4. Interpretation of exponential terms as transient dynamics.
5. Linear growth of position due to constant steady-state velocity.
6. Physical implications of unbounded position under constant torque.
