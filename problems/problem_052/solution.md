# Solution

## Method

With \( q = {12}\mathrm{\;{kW}}, w = {21} \times  {10}^{-6}{\mathrm{\;m}}^{3}/\mathrm{s} \neq  0 \) and \( {T}_{i} = {25}^{ \circ  }\mathrm{C} \)

\[
{mc}\dot{T} + \left( {{wc} + \frac{1}{R}}\right) T = q + {wc}{T}_{i} + \frac{1}{R}{T}_{o}.
\]

which has as solution

\[
T\left( t\right)  = \widetilde{T}\left( {1 - {e}^{\lambda t}}\right)  + T\left( 0\right) {e}^{\lambda t}
\]

where \( R = {0.27}\mathrm{\;K}/\mathrm{W} \) ,

\[
\lambda  =  - \frac{{Rwc} + 1}{Rmc} \approx   - {115.3} \times  {10}^{-6}{\mathrm{\;s}}^{-1}
\]

and

\[
\widetilde{T} = \frac{Rq}{{Rwc} + 1} + \frac{{Rwc}{T}_{i} + {T}_{o}}{{Rwc} + 1} \approx  {156.3}^{ \circ  }\mathrm{C}
\]

so that for \( T\left( 0\right)  = {25}^{ \circ  }\mathrm{C} \) and \( T\left( t\right)  = {60}^{ \circ  }\mathrm{C} \)

\[
t = \frac{1}{\lambda }\log \frac{T\left( t\right)  - \widetilde{T}}{T\left( 0\right)  - \widetilde{T}} \approx  {2690}\mathrm{\;s}
\]

or about 45 minutes. This is a 15% increase when compared to the case without flow.


## Teaching Points

1. Flow introduces an additional heat-loss mechanism.
2. Steady-state temperature decreases with increasing flow.
3. Heating time increases even if power input is unchanged.
4. The system remains first-order but with modified parameters.
