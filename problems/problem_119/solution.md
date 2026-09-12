# Solution

## Method
In response to a constant voltage

\[
{V}_{c}\left( s\right)  = G\left( s\right) \frac{\widetilde{v}}{s} = \frac{\widetilde{v}}{s}\frac{{\omega }_{n}^{2}}{{s}^{2} + {2\zeta }{\omega }_{n}s + {\omega }_{n}^{2}}
\]

The exact expansion in partial fractions will depend on the values of the coefficients to \( {\omega }_{n} \) and \( \zeta \). However, one can write:

\[
{V}_{c}\left( s\right)  = \widetilde{v}\left( {\frac{1}{s} - \frac{\left( s + 2\zeta {\omega }_{n}\right) }{{s}^{2} + {2\zeta }{\omega }_{n}s + {\omega }_{n}^{2}}}\right)
\]

from which one can identity the steady-state and transient components:

\[
{v}_{\mathrm{{ctr}}}\left( t\right)  =  - \widetilde{v}{\mathcal{L}}^{-1}\left\{  \frac{\left( s + 2\zeta {\omega }_{n}\right) }{{s}^{2} + {2\zeta }{\omega }_{n}s + {\omega }_{n}^{2}}\right\}  ,
\]

\[
{v}_{\text{ css }}\left( t\right)  = \widetilde{v}{\mathcal{L}}^{-1}\left\{  \frac{1}{s}\right\}   = \widetilde{v}.
\]

## Teaching Points
1. Step response of a second-order RLC system
2. Separation of transient and steady-state components using Laplace methods
3. Influence of damping ratio on transient decay and oscillations
4. Role of resistance in energy dissipation
5. Effect of inductance and capacitance on natural frequency and response speed
