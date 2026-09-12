# Solution

## Method
Assuming zero initial conditions, in the case of the sinsoidal torque, \( \tau \left( t\right) \) , and constant gravitational torque, \( w\left( t\right) \) , we set

\[
T\left( s\right)  = \frac{\widetilde{\tau }s}{{s}^{2} + {\omega }^{2}},\;W\left( s\right)  = \frac{\widetilde{w}}{s},\;\widetilde{w} = {gr}\left( {{m}_{1} - {m}_{2}}\right) ,
\]

and calculate

\[
{V}_{1}\left( s\right)  = {G}_{\tau }\left( s\right) T\left( s\right)  + {G}_{w}\left( s\right) W\left( s\right)  = \frac{\beta }{s + \alpha }\frac{\widetilde{\tau }s}{{s}^{2} + {\omega }^{2}} + \frac{\beta }{s + \alpha }\frac{\widetilde{w}}{s}
\]

Performing a partial fraction expansion as in (C.3)

\[
\frac{\beta s}{\left( {s + \alpha }\right) \left( {{s}^{2} + {\omega }^{2}}\right) } = \frac{\beta }{{2\omega }\left( {\alpha  - {j\omega }}\right) }\frac{1}{s + {j\omega }} + \frac{\beta }{{2\omega }\left( {\alpha  + {j\omega }}\right) }\frac{1}{s - {j\omega }} - \frac{\alpha \beta }{{\alpha }^{2} + {\omega }^{2}}\frac{1}{s + \alpha }
\]

and as in (C.1):

\[
\frac{\beta }{s\left( {s + \alpha }\right) } = \frac{\beta }{\alpha }\left( {\frac{1}{s} - \frac{1}{s + \alpha }}\right) .
\]

Combining these two

\[
{V}_{1}\left( s\right)  = \frac{\beta \widetilde{\tau }}{{2\omega }\left( {\alpha  - {j\omega }}\right) }\frac{1}{s + {j\omega }} + \frac{\beta \widetilde{\tau }}{{2\omega }\left( {\alpha  + {j\omega }}\right) }\frac{1}{s - {j\omega }} - \left( {\frac{{\alpha \beta }\widetilde{\tau }}{{\alpha }^{2} + {\omega }^{2}} + \frac{\beta \widetilde{w}}{\alpha }}\right) \frac{1}{s + \alpha } + \frac{\beta \widetilde{w}}{\alpha }\frac{1}{s},
\]

from which

\[
{v}_{1}\left( t\right)  = \frac{\beta \widetilde{\tau }}{{\alpha }^{2} + {\omega }^{2}}\left( {\omega \sin \left( {\omega t}\right)  + \alpha \cos \left( {\omega t}\right)  - \alpha {e}^{-{\alpha t}}}\right)  + \frac{\beta \widetilde{w}}{\alpha }\left( {1 - {e}^{-{\alpha t}}}\right) .
\]

The transient and steady-state components are

\[
{v}_{\mathrm{{ltr}}}\left( t\right)  =  - \left( {\frac{{\alpha \beta }\widetilde{\tau }}{{\alpha }^{2} + {\omega }^{2}} + \frac{\beta \widetilde{w}}{\alpha }}\right) {e}^{-{\alpha t}},
\]

\[
{v}_{1\mathrm{\;{ss}}}\left( t\right)  = \frac{\beta \widetilde{\tau }}{{\alpha }^{2} + {\omega }^{2}}\left( {\omega \sin \left( {\omega t}\right)  + \alpha \cos \left( {\omega t}\right) }\right)  + \frac{\beta \widetilde{w}}{\alpha }.
\]

## Teaching Points
1. System response to sinusoidal forcing in first-order systems.
2. Superposition of sinusoidal and constant inputs.
3. Use of complex poles in partial fraction expansion.
4. Interpretation of decaying exponentials as transient behavior.
5. Identification of steady-state sinusoidal response with amplitude and phase shift.
6. Effect of constant disturbances on steady-state operating point.
