# Solution



## Method

Using the mean-value theorem as in the previous question:

\[
f\left( \tau \right)  - f\left( 0\right)  = \tau \dot{f}\left( \xi \right) ,\;\xi  \in  \left\lbrack  {0,\tau }\right\rbrack  .
\]

so that

\[
{\int }_{{0}^{ - }}^{t}f\left( \tau \right) {p}_{\varepsilon }\left( \tau \right) {d\tau } = {\varepsilon }^{-1}{\int }_{{0}^{ - }}^{\varepsilon }f\left( \tau \right) {d\tau }
\]

\[
= {\varepsilon }^{-1}{\int }_{{0}^{ - }}^{\varepsilon }\left( {f\left( 0\right)  + \tau \dot{f}\left( \xi \right) }\right) {d\tau }
\]

\[
= {\varepsilon }^{-1}f\left( 0\right) {\int }_{{0}^{ - }}^{\varepsilon }{d\tau } + {\varepsilon }^{-1}\dot{f}\left( \xi \right) {\int }_{{0}^{ - }}^{\varepsilon }{\tau d\tau }
\]

\[
= {\left. f\left( 0\right)  + {\varepsilon }^{-1}\dot{f}\left( \xi \right) \frac{{\tau }^{2}}{2}\right| }_{{0}^{ - }}^{\varepsilon }
\]

\[
= f\left( 0\right)  + \frac{\varepsilon }{2}\dot{f}\left( \xi \right)
\]

from which

\[
\mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}{\int }_{{0}^{ - }}^{\infty }f\left( \tau \right) {p}_{\varepsilon }\left( \tau \right) {d\tau } = \mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}f\left( 0\right)  + \frac{\varepsilon }{2}\dot{f}\left( \xi \right)  = f\left( 0\right) .
\]

## Teaching Points
1. **Sampling Property**: This demonstrates that a narrow pulse of unit area acting on a function effectively "samples" the function's value at the pulse's location.
2. **First-Order Approximation**: Using the Mean-Value Theorem allows us to rigorously handle the "remainder" of the function variation within the pulse duration.
3. **Dirac Delta Intuition**: This result provides the mathematical justification for the property $\int_{-\infty}^{\infty} f(\tau)\delta(\tau)d\tau = f(0)$.
4. **Boundedness Requirement**: The proof assumes $\dot{f}$ is bounded, which is guaranteed by the differentiability of $f$ over the interval.