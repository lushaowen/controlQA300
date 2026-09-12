# Solution

## Method

In response to a constant force, \( f\left( t\right) = \widetilde{f} \), the Laplace transform of the mass position, \( X\left( s\right) \), is:

\[
X\left( s\right) = G\left( s\right) U\left( s\right) = \frac{1}{k}\frac{{\omega }_{n}^{2}}{{s}^{2} + {2\zeta }{\omega }_{n}s + {\omega }_{n}^{2}}\frac{\widetilde{f}}{s}.
\]

The exact expansion in partial fractions will depend on the values of the coefficients to \( {\omega }_{n} \) and \( \zeta \). However, one can write:

\[
X\left( s\right) = \frac{\widetilde{f}}{k}\left( {\frac{1}{s} - \frac{\left( s + 2\zeta {\omega }_{n}\right) }{{s}^{2} + {2\zeta }{\omega }_{n}s + {\omega }_{n}^{2}}}\right)
\]

from which one can identity the steady-state and transient components:

\[
{x}_{\mathrm{{tr}}}\left( t\right) = - \frac{\widetilde{f}}{k}{\mathcal{L}}^{-1}\left\{ \frac{\left( s + 2\zeta {\omega }_{n}\right) }{{s}^{2} + {2\zeta }{\omega }_{n}s + {\omega }_{n}^{2}}\right\},
\]

\[
{x}_{\mathrm{{ss}}}\left( t\right) = \frac{\widetilde{f}}{k}{\mathcal{L}}^{-1}\left\{ \frac{1}{s}\right\} = \frac{\widetilde{f}}{k}.
\]

The parameter \( k \) dictates the size of the steady-state response while the parameters \( b \) and \( m \) affect \( {\omega }_{n} \) and \( \zeta \), which will govern the transient response. See Chapter 6 and 7 for more details.

## Teaching Points

1. Use of Laplace transforms to analyze second-order dynamical systems.
2. Interpretation of steady-state response as the final value of a system.
3. Physical meaning of transient dynamics in mechanical systems.
4. Role of stiffness in determining equilibrium displacement.
5. Influence of mass and damping on oscillation frequency and decay rate.
6. Connection between mathematical parameters and physical system behavior.
