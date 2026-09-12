# Solution

## Method

Assuming zero-initial conditions and applying the Laplace transform

\[
{s}^{2}{m}_{1}{X}_{1}\left( s\right)  + s\left( {{b}_{1} + {b}_{2}}\right) {X}_{1}\left( s\right)  + \left( {{k}_{1} + {k}_{2}}\right) {X}_{1}\left( s\right)  - s{b}_{2}{X}_{2}\left( s\right)  - {k}_{2}{X}_{2}\left( s\right)  = 0,
\]

\[
{s}^{2}{m}_{2}{X}_{2}\left( s\right)  + s{b}_{2}\left( {{X}_{2}\left( s\right)  - {X}_{1}\left( s\right) }\right)  + {k}_{2}\left( {{X}_{2}\left( s\right)  - {X}_{1}\left( s\right) }\right)  = {F}_{2}\left( s\right) .
\]

Rearranging the second equation

\[
\left( {{m}_{2}{s}^{2} + {b}_{2}s + {k}_{2}}\right) {X}_{2}\left( s\right)  = {F}_{2}\left( s\right)  + \left( {{b}_{2}s + {k}_{2}}\right) {X}_{1}\left( s\right) .
\]

and solving for \( {X}_{2}\left( s\right) \)

\[
{X}_{2}\left( s\right)  = \frac{1}{{m}_{2}{s}^{2} + {b}_{2}s + {k}_{2}}{F}_{2}\left( s\right)  + \frac{{b}_{2}s + {k}_{2}}{{m}_{2}{s}^{2} + {b}_{2}s + {k}_{2}}{X}_{1}\left( s\right)
\]

which upon substitution in the first equation leads to

\[
\left( {{m}_{1}{s}^{2} + \left( {{b}_{1} + {b}_{2}}\right) s + \left( {{k}_{1} + {k}_{2}}\right) }\right) {X}_{1}\left( s\right)  = \left( {{b}_{2}s + {k}_{2}}\right) {X}_{2}\left( s\right)
\]

\[
= \frac{{b}_{2}s + {k}_{2}}{{m}_{2}{s}^{2} + {b}_{2}s + {k}_{2}}{F}_{2}\left( s\right)  + \frac{{\left( {b}_{2}s + {k}_{2}\right) }^{2}}{{m}_{2}{s}^{2} + {b}_{2}s + {k}_{2}}{X}_{1}\left( s\right)
\]

or

\[
{X}_{1}\left( s\right)  = G\left( s\right) {F}_{2}\left( s\right)
\]

where

\[
G\left( s\right)  = \frac{{b}_{2}s + {k}_{2}}{\left( {{m}_{2}{s}^{2} + {b}_{2}s + {k}_{2}}\right) \left( {{m}_{1}{s}^{2} + \left( {{b}_{1} + {b}_{2}}\right) s + {k}_{1} + {k}_{2}}\right)  - {\left( {b}_{2}s + {k}_{2}\right) }^{2}}.
\]

## Teaching Points

1. Modeling of coupled mechanical systems using differential equations.
2. Use of Laplace transforms to handle multi-degree-of-freedom systems.
3. Elimination of internal variables to derive transfer functions.
4. Interpretation of force-to-displacement transfer functions.
5. Recognition of higher-order dynamics due to system coupling.
6. Understanding how interconnecting elements introduce additional poles and zeros.
