# Solution
## Method 

\[
F\left( s\right) G\left( s\right)  = {\int }_{{0}^{ - }}^{\infty }f\left( \tau \right) {e}^{-{s\tau }}{d\tau G}\left( s\right)
\]

\[
= {\int }_{{0}^{ - }}^{\infty }f\left( \tau \right) {e}^{-{s\tau }}G\left( s\right) {d\tau }
\]

\[
= {\int }_{{0}^{ - }}^{\infty }f\left( \tau \right) \mathcal{L}\{ g\left( {t - \tau }\right) \} {d\tau }
\]

\[
= {\int }_{{0}^{ - }}^{\infty }f\left( \tau \right) {\int }_{{0}^{ - }}^{\infty }g\left( {t - \tau }\right) {e}^{-{st}}{dtd\tau }
\]

\[
= {\int }_{{0}^{ - }}^{\infty }{\int }_{{0}^{ - }}^{\infty }f\left( \tau \right) g\left( {t - \tau }\right) {d\tau }{e}^{-{st}}{dt}
\]

\[
= \mathcal{L}\left\{  {{\int }_{{0}^{ - }}^{\infty }f\left( \tau \right) g\left( {t - \tau }\right) {d\tau }}\right\}
\]

\[
= \mathcal{L}\left\{  {{\int }_{{0}^{ - }}^{t}f\left( \tau \right) g\left( {t - \tau }\right) {d\tau }}\right\}  .
\]

The last expression follows from the fact that \( g\left( t\right)  = 0 \) for \( t < 0 \) .



## Teaching Points

1. Multiplication in the \( s \)-domain corresponds to convolution in time.
2. Causality determines the integration limits.
3. The convolution property is fundamental to system response analysis.
4. This result underpins transfer-function-based modeling.
