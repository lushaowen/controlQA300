# Solution

## Method
 \( G\left( s\right)  = \beta /\left( {s + \alpha }\right) ,\alpha  > 0 \) , which is asymptotically stable. Therefore, the steady state response to a constant torque \( \tau \left( t\right)  = \widetilde{\tau } \) is given by

\[
{\omega }_{2\mathrm{{ss}}}\left( t\right)  = G\left( {j0}\right) \widetilde{\tau } = \frac{\beta \widetilde{\tau }}{\alpha } = \frac{\left( {{r}_{1}/{r}_{2}}\right) \widetilde{\tau }}{{b}_{1} + {b}_{2}{\left( {r}_{1}/{r}_{2}\right) }^{2}}.
\]

In P3.56 the steady state response to a constant sinusoidal torque \( \tau \left( t\right)  = \widetilde{\tau }\cos \left( {\omega t}\right) \) is given by

\[
{\omega }_{2\mathrm{{ss}}}\left( t\right)  = \widetilde{\tau }\left| {G\left( {j\omega }\right) }\right| \cos ({\omega t} + \angle G\left( {j\omega }\right)
\]

where

\[
\left| {G\left( {j\omega }\right) }\right|  = \frac{\beta }{\left| j\omega  + \alpha \right| } = \frac{\beta }{\sqrt{{\omega }^{2} + {\alpha }^{2}}},\;\angle G\left( {j\omega }\right)  = \angle \frac{\beta }{{j\omega } + \alpha } =  - {\tan }^{-1}\frac{\omega }{\alpha },
\]

which coincides with the previous answer since with \( \alpha  > 0 \)

\[
\cos \left( {{\omega t} - {\tan }^{-1}\omega /\alpha }\right)  = \frac{1}{\sqrt{{\omega }^{2} + {\alpha }^{2}}}\left( {\omega \sin \left( {\omega t}\right)  + \alpha \cos \left( {\omega t}\right) }\right) .
\]


## Teaching Points
1. Conditions under which frequency-response methods are applicable
2. Importance of asymptotic stability for steady-state analysis
3. Relationship between Laplace-domain solutions and frequency-response results
4. Interpretation of steady-state behavior independent of transient dynamics
5. Comparison of time-domain and frequency-domain solution techniques
