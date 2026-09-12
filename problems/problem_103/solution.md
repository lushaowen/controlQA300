# Solution

## Method
Assuming zero initial conditions, in the case of the sinsoidal torque we set

\[
T\left( s\right)  = \frac{\widetilde{\tau }s}{{s}^{2} + {\omega }^{2}}
\]

and calculate

\[
{\Omega }_{2}\left( s\right)  = G\left( s\right) T\left( s\right)  = \frac{\beta }{s + \alpha }\frac{s}{{s}^{2} + {\omega }^{2}}\widetilde{\tau } = \frac{\beta s}{\left( {s + \alpha }\right) \left( {{s}^{2} + {\omega }^{2}}\right) }\widetilde{\tau },
\]

where \( \alpha \) and \( \beta \) are as in P3.54. Expanding in partial fractions:

\[
\frac{\beta s}{\left( {s + \alpha }\right) \left( {{s}^{2} + {\omega }^{2}}\right) } = \frac{\beta }{{2\omega }\left( {\alpha  - {j\omega }}\right) }\frac{1}{s + {j\omega }} + \frac{\beta }{{2\omega }\left( {\alpha  + {j\omega }}\right) }\frac{1}{s - {j\omega }} - \frac{\alpha \beta }{{\alpha }^{2} + {\omega }^{2}}\frac{1}{s + \alpha } \tag{C.3}
\]

from which

\[
{\mathcal{L}}^{-1}\left\{  {\frac{\beta }{\left( {s + \alpha }\right) \left( {{s}^{2} + {\omega }^{2}}\right) }\widetilde{\tau }}\right\}   = {\mathcal{L}}^{-1}\left\{  {\frac{\beta }{{2\omega }\left( {\alpha  - {j\omega }}\right) }\frac{1}{s + {j\omega }} + \frac{\beta }{{2\omega }\left( {\alpha  + {j\omega }}\right) }\frac{1}{s - {j\omega }}}\right\}   -
\]

\[
{\mathcal{L}}^{-1}\left\{  {\frac{\alpha \beta }{{\alpha }^{2} + {\omega }^{2}}\frac{1}{s + \alpha }}\right\}   = \frac{\beta }{{\alpha }^{2} + {\omega }^{2}}\left( {\omega \sin \left( {\omega t}\right)  + \alpha \cos \left( {\omega t}\right)  - \alpha {e}^{-{\alpha t}}}\right) \tag{C.4}
\]

and

\[
{\omega }_{2}\left( t\right)  = \frac{\beta \widetilde{\tau }}{{\alpha }^{2} + {\omega }^{2}}\left( {\omega \sin \left( {\omega t}\right)  + \alpha \cos \left( {\omega t}\right)  - \alpha {e}^{-{\alpha t}}}\right) .
\]

The transient and steady-state components are

\[
{\omega }_{2\mathrm{{tr}}}\left( t\right)  =  - \frac{{\alpha \beta }\widetilde{\tau }}{{\alpha }^{2} + {\omega }^{2}}{e}^{-{\alpha t}},
\]

\[
{\omega }_{2\mathrm{{ss}}}\left( t\right)  = \frac{\beta \widetilde{\tau }}{{\alpha }^{2} + {\omega }^{2}}\left( {\omega \sin \left( {\omega t}\right)  + \alpha \cos \left( {\omega t}\right) }\right) .
\]

## Teaching Points
1. Laplace-domain representation of sinusoidal inputs
2. Handling complex poles in partial-fraction expansions
3. Relationship between time-domain sinusoidal steady-state and frequency response
4. Identification of exponentially decaying transient terms
5. Effect of damping parameter \( \alpha \) on transient decay rate
6. Amplitude and phase characteristics of steady-state sinusoidal responses
