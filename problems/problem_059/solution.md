# Solution

## Method
We seek to evaluate:

\[
\mathcal{L}\left\{  \frac{{df}\left( t\right) }{dt}\right\}   = {\int }_{{0}^{ - }}^{\infty }\frac{{df}\left( t\right) }{dt}{e}^{-{st}}{dt}.
\]

Integrating by parts with \( u = {e}^{-{st}} \) and \( {dv} = \frac{{df}\left( t\right) }{dt}{dt} \) :

\[
{\int }_{{0}^{ - }}^{\infty }\frac{{df}\left( t\right) }{dt}{e}^{-{st}}{dt} = {\left. f\left( t\right) {e}^{-{st}}\right| }_{{0}^{ - }}^{\infty } + {\int }_{{0}^{ - }}^{\infty }f\left( t\right) s{e}^{-{st}}{dt}
\]

\[
= {\left. sF\left( s\right)  + f\left( t\right) {e}^{-{st}}\right| }_{{0}^{ - }}^{\infty }
\]

If \( \left| {f\left( t\right) }\right|  \leq  M{e}^{\alpha t} \) then for any \( s = \beta  + {j\gamma } \)

\[
\left| {f\left( t\right) {e}^{-{st}}}\right|  \leq  M{e}^{\left( {\alpha  - \beta }\right) t}
\]

so that for \( \beta \) large enough

\[
{\left. f\left( t\right) {e}^{-{st}}\right| }_{{0}^{ - }}^{\infty } = f\left( {0}^{ - }\right) ,
\]

which proves the differentiation property.


## Teaching Points

1. Differentiation in time corresponds to multiplication by \( s \) in the Laplace domain.
2. Initial conditions appear naturally through boundary terms.
3. Exponential growth conditions ensure convergence of the transform.
4. Integration by parts is central to proving transform properties.
5. This property is fundamental for solving differential equations using Laplace transforms.
