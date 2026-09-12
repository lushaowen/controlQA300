# Solution

## Method
We seek to evaluate:

\[
\mathcal{L}\left\{  {{\int }_{{0}^{ - }}^{t}f\left( \tau \right) {d\tau }}\right\}   = {\int }_{{0}^{ - }}^{\infty }{\int }_{{0}^{ - }}^{t}f\left( \tau \right) {d\tau }{e}^{-{st}}{dt}.
\]

Integrating by parts with \( u = {\int }_{{0}^{ - }}^{t}f\left( \tau \right) {d\tau } \) and \( {dv} = {e}^{-{st}}{dt} \) :

\[
{\int }_{{0}^{ - }}^{\infty }{\int }_{{0}^{ - }}^{t}f\left( \tau \right) {d\tau }{e}^{-{st}}{dt} =  - {\left. \frac{{e}^{-{st}}}{s}{\int }_{{0}^{ - }}^{t}f\left( \tau \right) d\tau \right| }_{{0}^{ - }}^{\infty } - {\int }_{{0}^{ - }}^{\infty }f\left( t\right) \frac{-{e}^{-{st}}}{s}{dt}
\]

\[
= \frac{F\left( s\right) }{s} +  - {\left. \frac{{e}^{-{st}}}{s}{\int }_{{0}^{ - }}^{t}f\left( \tau \right) d\tau \right| }_{{0}^{ - }}^{\infty }
\]

If \( \left| {f\left( t\right) }\right|  \leq  M{e}^{\alpha t} \) then for any \( s = \beta  + {j\gamma } \)

\[
\left| {{e}^{-{st}}{\int }_{{0}^{ - }}^{t}f\left( \tau \right) {d\tau }}\right|  \leq  \left| {e}^{-{st}}\right| {\int }_{{0}^{ - }}^{t}\left| {f\left( \tau \right) }\right| {d\tau } \leq  M\left| {e}^{-{st}}\right| {\int }_{{0}^{ - }}^{t}{e}^{\alpha \tau }{d\tau } = \frac{M}{\alpha }{e}^{\left( {\alpha  - \beta }\right) t}
\]

so that for \( \beta \) large enough

\[
-{\left. \frac{{e}^{-{st}}}{s}{\int }_{{0}^{ - }}^{t}f\left( \tau \right) d\tau \right| }_{{0}^{ - }}^{\infty } = 0,
\]

which proves the integration property.


## Teaching Points

1. Integration properties follow directly from the definition of the Laplace transform.
2. Integration by parts is a key analytical tool in transform proofs.
3. Exponential order ensures convergence of boundary terms.
4. The integration property simplifies system analysis involving accumulators.
5. This result is fundamental in control systems and signal modeling.
