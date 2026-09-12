# Solution


## Method

The differential equation can be rewritten as

\[
\dot{\omega } + {\alpha \omega } = \beta {v}_{a}
\]

where

\[
\alpha  = \frac{b}{J} + \frac{{K}_{t}{K}_{e}}{J{R}_{a}},
\]

The solution to the differential equation when \( {v}_{a} = {\bar{v}}_{a} \) is constant is

\[
\omega \left( t\right)  = \widetilde{\omega }\left( {1 - {e}^{\lambda t}}\right)  + \omega \left( 0\right) {e}^{-{\lambda t}},\;\lambda  =  - \alpha ,\;\widetilde{\omega } = \frac{\beta }{\alpha }{\bar{v}}_{a}.
\]

Knowing that when \( {\bar{v}}_{a} = {12}\mathrm{\;V} \) the time-constant is equal to 0.1s and the terminal velocity is 5000RPM means that

\[
\lambda  =  - \alpha  =  - 1/{0.1} =  - {10}{\mathrm{\;s}}^{-1},\;\widetilde{\omega } = \frac{\beta {\bar{v}}_{a}}{\alpha } = {5000}\mathrm{{RPM}}\text{ , }
\]

from which it is possible to estimate

\[
\alpha  = {10}{\mathrm{\;s}}^{-1},\;\beta  = \frac{\widetilde{\omega }\alpha }{{\bar{v}}_{a}} = \frac{{5000} \times  {10}}{12} \approx  {4166}\frac{\mathrm{{RPM}}}{\mathrm{{Vs}}}.
\]

In SI units

\[
\beta  = \frac{2\pi }{60}{4166} \approx  {436.3}\frac{\mathrm{{rad}}}{\mathrm{V}{\mathrm{s}}^{2}}.
\]

There is not enough information to estimate all physical parameters.

## Teaching Points

1. Stall tests provide direct access to torque-related parameters
2. Zero-speed conditions eliminate back-EMF effects
3. Electrical measurements can reveal mechanical properties
4. DC motor constants are often symmetric in SI units
5. Parameter estimation bridges theory and experiment
