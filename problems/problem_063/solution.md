# Solution


## Method
We seek to calculate

\[
\mathcal{L}\left\{  {{e}^{-{at}}f\left( t\right) }\right\}   = {\int }_{{0}^{ - }}^{\infty }{e}^{-{at}}f\left( t\right) {e}^{-{st}}{dt}
\]

\[
= {\int }_{{0}^{ - }}^{\infty }f\left( t\right) {e}^{-\left( {s + a}\right) t}{dt} = F\left( {s + a}\right) .
\]
## Teaching Points

1. Multiplication by an exponential in time causes a shift in the \( s \)-domain.
2. The Laplace transform variable is shifted by \( +a \).
3. This property is often called the *complex-frequency shift*.
4. Frequency shifting is fundamental in stability and region-of-convergence analysis.
5. The property is widely used in control and signal processing.
