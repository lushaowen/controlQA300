# Solution

## Method

Applying the Laplace transform

\[
U\left( s\right)  = \left( {{K}_{p} + {K}_{p}{T}_{d}s + \frac{{K}_{p}}{{T}_{i}s}}\right) \left( {Y\left( s\right)  - \bar{Y}\left( s\right) }\right)
\]

\[
= {K}_{p}\frac{1 + {T}_{i}s + {T}_{i}{T}_{d}{s}^{2}}{{T}_{i}s}\left( {Y\left( s\right)  - \bar{Y}\left( s\right) }\right)
\]

\[
= {K}_{p}K\left( s\right) \left( {Y\left( s\right)  - \bar{Y}\left( s\right) }\right) ,\;K\left( s\right)  = \frac{1 + {T}_{i}s + {T}_{i}{T}_{d}{s}^{2}}{{T}_{i}s}.
\]

Substituting numeric values

\[
K\left( s\right)  = \frac{1 + {100s} + {3800}{s}^{2}}{100s}.
\]

The loop transfer-function is obtained from

\[
\frac{\widetilde{Y}\left( s\right) }{E\left( s\right) } = \frac{\widetilde{Y}\left( s\right) }{\widetilde{Y}\left( s\right)  - Y\left( s\right) }
\]

\[
= \frac{\widetilde{Y}\left( s\right) }{\widetilde{U}\left( s\right) }\frac{\widetilde{U}\left( s\right) }{\widetilde{Y}\left( s\right)  - Y\left( s\right) }
\]

\[
=  - {K}_{p}K\left( s\right) \frac{-{gb}{\bar{x}}_{2}}{\left( {s + f}\right) \left( {s + a}\right) \left( {s + c + {\bar{x}}_{1}}\right) }
\]

\[
= {K}_{p}L\left( s\right) ,\;L\left( s\right)  = \frac{{gb}{\bar{x}}_{2}\left( {1 + {T}_{i}s + {T}_{i}{T}_{d}{s}^{2}}\right) }{{T}_{i}s\left( {s + f}\right) \left( {s + a}\right) \left( {s + c + {\bar{x}}_{1}}\right) }
\]

Substituting numeric values

\[
L\left( s\right)  = {3.3}\left( {1/5}\right) {\left( 1/{33}\right) }^{2}\frac{1 + {100s} + {3800}{s}^{2}}{s\left( {s + 1/5}\right) {\left( s + 1/{33}\right) }^{2}} = {3.3}\frac{1 + {100s} + {3800}{s}^{2}}{s\left( {1 + {5s}}\right) {\left( 1 + {33}s\right) }^{2}}
\]

## Teaching Points
1. Conversion of PID laws into transfer-function form
2. Interpretation of integral and derivative action in root-locus analysis
3. Construction of loop transfer-functions from linearized physiological models
4. Effect of multiple poles near the origin on stability
5. Use of experimental parameters in control-theoretic analysis
6. Validation of biological feedback mechanisms using classical control tools
