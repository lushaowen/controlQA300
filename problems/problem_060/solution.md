# Solution


## Method
We seek to calculate

\[
\mathcal{L}\left\{  \frac{{d}^{2}f\left( t\right) }{d{t}^{2}}\right\}
\]

Let \( g\left( t\right)  = {df}\left( t\right) /{dt} \) and calculate

\[
\mathcal{L}\left\{  \frac{{d}^{2}f\left( t\right) }{d{t}^{2}}\right\}   = \mathcal{L}\left\{  \frac{{dg}\left( t\right) }{dt}\right\}
\]

\[
= {sG}\left( s\right)  - g\left( {0}^{ - }\right) .
\]

But since

\[
G\left( s\right)  = \mathcal{L}\left\{  \frac{{df}\left( t\right) }{dt}\right\}
\]

\[
= {sF}\left( s\right)  - f\left( {0}^{ - }\right)
\]

we obtain

\[
\mathcal{L}\left\{  \frac{{d}^{2}f\left( t\right) }{d{t}^{2}}\right\}   = s\left( {{sF}\left( s\right)  - f\left( {0}^{ - }\right) }\right)  - {f}^{\prime }\left( {0}^{ - }\right)
\]

\[
\left. { = {s}^{2}F\left( s\right)  - {sf}\left( {0}^{ - }\right) }\right)  - {f}^{\prime }\left( {0}^{ - }\right) .
\]

Derivatives of higher order follow similarly.


## Teaching Points

1. Higher-order differentiation properties follow from repeated application of the first-order case.
2. Each differentiation introduces an additional initial-condition term.
3. Initial conditions naturally appear in the Laplace domain.
4. This property converts differential equations into algebraic equations.
5. The result is essential for solving high-order linear differential equations in control systems.
