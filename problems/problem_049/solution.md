# Solution

## Method


With \( q = 0 \) and \( w = 0 \)

\[
{mc}\dot{T} + \frac{1}{R}T = \frac{1}{R}{T}_{o}
\]

which has as solution

\[
T\left( t\right)  = \widetilde{T}\left( {1 - {e}^{\lambda t}}\right)  + T\left( 0\right) {e}^{\lambda t}
\]

where

\[
\lambda  =  - \frac{1}{Rmc},
\]

With \( T\left( 0\right)  = {60}^{ \circ  }\mathrm{C} \) and \( {T}_{o} = {25}^{ \circ  }\mathrm{C} \) , after 7 days \( t = 7 \times  {24} \times  {3600} = {604800}\mathrm{\;s} \) and

\[
{25} + \left( {{60} - {25}}\right) {e}^{\lambda t} = T\left( t\right)  = {27}
\]

or

\[
\lambda  = \frac{1}{604800}\log \frac{{27} - {25}}{{60} - {25}} \approx   - {4.73} \times  {10}^{-6}{\mathrm{\;s}}^{-1},
\]

from which \( m = {997.1} \times  {0.19} \approx  {189}\mathrm{\;{kg}}, c = {4186}\mathrm{\;J}/\mathrm{{kg}}\mathrm{\;K} \) and

\[
R =  - \frac{1}{mc\lambda } \approx  {0.27}\mathrm{\;K}/\mathrm{W}
\]
## Teaching Points

1. Thermal resistance can be identified from transient temperature data.
2. Even simple first-order models can yield realistic physical parameters.
3. Long time constants are typical for well-insulated thermal systems.
4. This problem mirrors parameter estimation in electrical and mechanical systems.
5. Lumped thermal models are effective for energy storage systems.
