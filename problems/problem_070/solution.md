# Solution

## Method

Use the mean-value theorem to write:

\[
{\int }_{{0}^{ - }}^{\infty }f\left( {t - \tau }\right) {p}_{\varepsilon }\left( \tau \right) {d\tau } = {\varepsilon }^{-1}{\int }_{{0}^{ - }}^{\varepsilon }f\left( {t - \tau }\right) {d\tau }
\]

\[
= {\varepsilon }^{-1}{\int }_{{0}^{ - }}^{\varepsilon }\left( {f\left( t\right)  - \tau \dot{f}\left( \xi \right) }\right) {d\tau }
\]

\[
= {\varepsilon }^{-1}f\left( t\right) {\int }_{{0}^{ - }}^{\varepsilon }{d\tau } - {\varepsilon }^{-1}\dot{f}\left( \xi \right) {\int }_{{0}^{ - }}^{\varepsilon }{\tau d\tau }
\]

\[
= {\left. f\left( t\right)  - {\varepsilon }^{-1}\dot{f}\left( \xi \right) \frac{{\tau }^{2}}{2}\right| }_{{0}^{ - }}^{\varepsilon }
\]

\[
= f\left( t\right)  - \frac{\varepsilon }{2}\dot{f}\left( \xi \right)
\]

from which

\[
\mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}{\int }_{{0}^{ - }}^{\infty }f\left( {t - \tau }\right) {p}_{\varepsilon }\left( \tau \right) {d\tau } = \mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}f\left( t\right)  + \frac{\varepsilon }{2}\dot{f}\left( \xi \right)  = f\left( t\right) .
\]


## Teaching Points
1. **Sifting Property**: This exercise proves how a pulse function "picks out" or "sifts" the value of another function at a specific point in the limit.
2. **Mean-Value Theorem in Analysis**: Shows a practical application of the MVT to approximate functions within integrals.
3. **Approximation of the Dirac Delta**: Demonstrates that the limit of the pulse function $p_{\epsilon}(\tau)$ behaves like the Dirac Delta function $\delta(\tau)$, where $\int f(t-\tau)\delta(\tau)d\tau = f(t)$.
4. **Order of Magnitude**: Note that the error term is of order $O(\epsilon)$, confirming that the approximation improves linearly as the pulse narrows.