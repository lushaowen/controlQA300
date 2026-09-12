# Solution

## Method
Assuming zero initial conditions, in the case of the sinsoidal torque we set

\[
T\left( s\right)  = \frac{\widetilde{\tau }s}{{s}^{2} + {\omega }^{2}}
\]

and calculate

\[
{\Theta }_{2}\left( s\right)  = H\left( s\right) T\left( s\right)  = \frac{\beta }{s\left( {s + \alpha }\right) }\frac{s}{{s}^{2} + {\omega }^{2}}\widetilde{\tau } = \frac{\beta }{\left( {s + \alpha }\right) \left( {{s}^{2} + {\omega }^{2}}\right) }\widetilde{\tau },
\]

where \( \alpha \) and \( \beta \) are as in P3.54. Note the cancelation of the pole at \( s = 0 \) . Expanding in partial fractions:

\[
\frac{\beta }{\left( {s + \alpha }\right) \left( {{s}^{2} + {\omega }^{2}}\right) } = \frac{\beta }{{\alpha }^{2} + {\omega }^{2}}\frac{1}{s + \alpha } + \frac{j\beta }{{2\omega }\left( {\alpha  - {j\omega }}\right) }\frac{1}{s + {j\omega }} - \frac{j\beta }{{2\omega }\left( {\alpha  + {j\omega }}\right) }\frac{1}{s - {j\omega }} \tag{C.7}
\]

from which

\[
{\mathcal{L}}^{-1}\left\{  \frac{\beta }{\left( {s + \alpha }\right) \left( {{s}^{2} + {\omega }^{2}}\right) }\right\}   = {\mathcal{L}}^{-1}\left\{  {\frac{\beta }{{\alpha }^{2} + {\omega }^{2}}\frac{1}{s + \alpha }}\right\}   +
\]

\[
{\mathcal{L}}^{-1}\left\{  {\frac{j\beta }{{2\omega }\left( {\alpha  - {j\omega }}\right) }\frac{1}{s + {j\omega }} - \frac{j\beta }{{2\omega }\left( {\alpha  + {j\omega }}\right) }\frac{1}{s - {j\omega }}}\right\}   =
\]

\[
\frac{\beta }{{\alpha }^{2} + {\omega }^{2}}\left( {{e}^{-{\alpha t}} + \frac{\alpha }{\omega }\sin \left( {\omega t}\right)  - \cos \left( {\omega t}\right) }\right) \tag{C.8}
\]

and

\[
{\theta }_{2}\left( t\right)  = \frac{\beta \widetilde{\tau }}{{\alpha }^{2} + {\omega }^{2}}\left( {{e}^{-{\alpha t}} + \frac{\alpha }{\omega }\sin \left( {\omega t}\right)  - \cos \left( {\omega t}\right) }\right) .
\]

The transient and steady-state components are

\[
{\theta }_{2\mathrm{{tr}}}\left( t\right)  = \frac{\beta \widetilde{\tau }}{{\alpha }^{2} + {\omega }^{2}}{e}^{-{\alpha t}},
\]

\[
{\theta }_{2\mathrm{\;s}\mathrm{s}}\left( t\right)  = \frac{\beta \widetilde{\tau }}{{\alpha }^{2} + {\omega }^{2}}\left( {\frac{\alpha }{\omega }\sin \left( {\omega t}\right)  - \cos \left( {\omega t}\right) }\right) .
\]

## Teaching Points
1. Representation of sinusoidal inputs using Laplace transforms.
2. Use of transfer functions to relate input torque to angular displacement.
3. Identification and significance of pole-zero cancellation in system dynamics.
4. Application of partial fraction expansion with complex conjugate poles.
5. Separation of transient and steady-state responses in time-domain solutions.
6. Physical interpretation of exponential decay and steady sinusoidal oscillations.
