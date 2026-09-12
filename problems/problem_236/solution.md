# Solution

## Method
Recall, we have the following transfer function from \( \widetilde{u} \) to \( \widetilde{y} \) ,

\[
\frac{\widetilde{Y}\left( s\right) }{\widetilde{U}\left( s\right) } = \frac{-{gb}{\bar{x}}_{2}}{\left( {s + f}\right) \left( {s + a}\right) \left( {s + c + {\bar{x}}_{1}}\right) },
\]

where \( g = {0.2}, f = {0.2}, a = 1/{33}, b = {3.0303} \times  {10}^{-5},{\bar{x}}_{2} = {100} \) and \( c + {\bar{x}}_{1} = 1/{33} \) . Additionally, our controller has the transfer function

\[
K\left( s\right)  = \frac{{K}_{p}}{{T}_{i}}\frac{{s}^{2}{T}_{i}{T}_{d} + {T}_{i}s + 1}{s},
\]

where \( {T}_{i} = {100} \) and \( {T}_{d} = {38} \) .

Noting that our controller acts in positive feedback - namely that \( E\left( s\right)  = Y\left( s\right)  - \bar{Y}\left( s\right) \) , we have the following loop-transfer function

\[
L\left( s\right)  = {K}_{p}\frac{{gb}{\bar{x}}_{2}\left( {1 + {T}_{i}s + {T}_{i}{T}_{d}{s}^{2}}\right) }{{T}_{i}s\left( {s + f}\right) \left( {s + a}\right) \left( {s + c + {\bar{x}}_{1}}\right) }.
\]

The corresponding Bode plots and Nyquist diagrams are provided in Figure G.27. As seen in the Nyquist diagram, no point on the negative real axis is encircled. Given that the open-loop transfer function has no poles in the right-hand plane, this guarantees asymptotic stability for any \( {K}_{p} > 0 \) .

## Teaching Points
1. Modeling of glucose–insulin dynamics using linearized transfer functions.
2. Structure and interpretation of PID controllers in frequency domain.
3. Construction of loop transfer functions for feedback analysis.
4. Role of positive feedback sign conventions in physiological control systems.
5. Use of Bode plots to understand gain and phase characteristics.
6. Application of Nyquist stability criterion for nonlinear biological systems.
7. Interpretation of asymptotic stability for all positive proportional gains.
