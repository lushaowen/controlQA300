# Problem

## Problem Description
 with a sinusoidal in/out flow perturbation

\[
w\left( t\right)  = \frac{\bar{w}}{2}\left( {1 + \cos \left( {\omega t}\right) }\right),
\]

where \( \bar{w} = {20}\mathrm{{gal}}/\mathrm{h}\left( { \approx  {21} \times  {10}^{-6}{\mathrm{\;m}}^{3}/\mathrm{s}}\right) \) at ambient temperature and

\[
\omega  = {2\pi }/{24}{\mathrm{\;h}}^{-1}.
\]

Approximate

\[
w\left( t\right) \left( {{T}_{\mathrm{i}} - T\left( t\right) }\right)
\approx
w\left( t\right) \left( {{T}_{\mathrm{i}} - \bar{T}}\right).
\]

## Subproblems
1. Modify the thermal model  to account for a nonzero, time-varying flow rate.
2. Justify the approximation \( w(t)(T_i - T(t)) \approx w(t)(T_i - \bar{T}) \).
3. Derive the resulting transfer function from heat input \( q \) to temperature \( T \).
4. Identify the frequencies present in the reference/disturbance signals.
5. Explain why tracking a constant plus sinusoidal signal requires additional controller poles.
6. Propose a controller structure that embeds the required intern
