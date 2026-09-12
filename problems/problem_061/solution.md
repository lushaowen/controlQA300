# Solution



## Method

We seek to calculate

\[
\frac{{dF}\left( s\right) }{ds} = \frac{d}{ds}{\int }_{{0}^{ - }}^{\infty }f\left( t\right) {e}^{-{st}}{dt}
\]

\[
= {\int }_{{0}^{ - }}^{\infty }\frac{d}{ds}\left\{  {f\left( t\right) {e}^{-{st}}}\right\}  {dt}
\]

\[
= {\int }_{{0}^{ - }}^{\infty }\left( {-t}\right) f\left( t\right) {e}^{-{st}}{dt} = \mathcal{L}\{ \left( {-t}\right) f\left( t\right) \}
\]

which is the desired result. Derivatives of higher order follow similarly.


## Teaching Points

1. Differentiation in the \( s \)-domain corresponds to time-weighting in the time domain.
2. The negative sign arises naturally from differentiating the exponential kernel.
3. This property complements the time differentiation property.
4. Higher-order \( s \)-derivatives introduce higher powers of \( t \).
5. The result is useful in moment calculations and system sensitivity analysis.
