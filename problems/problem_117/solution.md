# Solution

## Method
Assuming zero initial conditions, in the case of the sinsoidal torque we set

\[
V\left( s\right)  = \frac{\widetilde{v}s}{{s}^{2} + {\omega }^{2}}
\]

and calculate

\[
{V}_{c}\left( s\right)  = G\left( s\right) T\left( s\right)  = \frac{\beta }{s + \alpha }\frac{s}{{s}^{2} + {\omega }^{2}}\widetilde{v} = \frac{\beta s}{\left( {s + \alpha }\right) \left( {{s}^{2} + {\omega }^{2}}\right) }\widetilde{v},
\]

where \( \alpha  = \beta  = 1/{RC} \) are as in P3.80. Expanding in partial fractions as in (C.3) and (C.4):

\[
{\mathcal{L}}^{-1}\left\{  {\frac{\beta }{\left( {s + \alpha }\right) \left( {{s}^{2} + {\omega }^{2}}\right) }\widetilde{\tau }}\right\}   = {\mathcal{L}}^{-1}\left\{  {\frac{\beta }{{2\omega }\left( {\alpha  - {j\omega }}\right) }\frac{1}{s + {j\omega }} + \frac{\beta }{{2\omega }\left( {\alpha  + {j\omega }}\right) }\frac{1}{s - {j\omega }}}\right\}   -
\]

\[
{\mathcal{L}}^{-1}\left\{  {\frac{\alpha \beta }{{\alpha }^{2} + {\omega }^{2}}\frac{1}{s + \alpha }}\right\}   = \frac{\beta }{{\alpha }^{2} + {\omega }^{2}}\left( {\omega \sin \left( {\omega t}\right)  + \alpha \cos \left( {\omega t}\right)  - \alpha {e}^{-{\alpha t}}}\right)
\]

from which

\[
{v}_{c}\left( t\right)  = \frac{\beta \widetilde{v}}{{\alpha }^{2} + {\omega }^{2}}\left( {\omega \sin \left( {\omega t}\right)  + \alpha \cos \left( {\omega t}\right)  - \alpha {e}^{-{\alpha t}}}\right) .
\]

The transient and steady-state components are

\[
{v}_{\mathrm{{ctr}}}\left( t\right)  =  - \frac{{\alpha \beta }\widetilde{v}}{{\alpha }^{2} + {\omega }^{2}}{e}^{-{\alpha t}} =  - \frac{\widetilde{v}}{1 + {\left( \omega /\alpha \right) }^{2}}{e}^{-{\alpha t}},
\]

\[
{v}_{\text{ css }}\left( t\right)  = \frac{\beta \widetilde{v}}{{\alpha }^{2} + {\omega }^{2}}\left( {\omega \sin \left( {\omega t}\right)  + \alpha \cos \left( {\omega t}\right) }\right)  = \frac{\widetilde{v}}{1 + {\left( \omega /\alpha \right) }^{2}}\left( {\frac{\omega }{\alpha }\sin \left( {\omega t}\right)  + \cos \left( {\omega t}\right) }\right) .
\]

## Teaching Points
1. Sinusoidal steady-state analysis using Laplace transforms
2. Relationship between time-domain response and frequency response
3. Decomposition of system response into transient and steady-state parts
4. Frequency-dependent attenuation and phase shift in RC circuits
5. Physical interpretation of exponential decay in driven systems
