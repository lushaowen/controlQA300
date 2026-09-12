# Solution

## Method

We seek to calculate

\[
\mathcal{L}\{ f\left( {t - \tau }\right) 1\left( {t - \tau }\right) \}  = {\int }_{{0}^{ - }}^{\infty }f\left( {t - \tau }\right) 1\left( {t - \tau }\right) {e}^{-{st}}{dt},\;\sigma  = t - \tau ,\;{d\sigma } = {dt},
\]

\[
= {\int }_{{0}^{ - }}^{\infty }f\left( \sigma \right) 1\left( \sigma \right) {e}^{-s\left( {\sigma  + \tau }\right) }{dt},
\]

\[
= {e}^{-{\tau s}}{\int }_{{0}^{ - }}^{\infty }f\left( \sigma \right) 1\left( \sigma \right) {e}^{-{s\sigma }}{dt},
\]

\[
= {e}^{-{\tau s}}{e}^{-{\tau s}}F\left( s\right) .
\]
## Teaching Points

1. Time delay in the time domain corresponds to multiplication by \( e^{-\tau s} \) in the Laplace domain.
2. The unit step function ensures causality after shifting.
3. Change of variables is a powerful tool in transform proofs.
4. This property is fundamental in modeling transport delays.
5. Time-shift properties are heavily used in control and signal processing.
