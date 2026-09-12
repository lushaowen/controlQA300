# Solution

## Method

Starting with

\[
\sin \left( {at}\right) /t = {\int }_{0}^{a}\cos \left( {at}\right) {da}
\]

calculate

\[
\mathcal{L}\{ \sin \left( {at}\right) /t\}  = {\int }_{{0}^{ - }}^{\infty }{\int }_{0}^{a}\cos \left( {at}\right) {da}{e}^{-{st}}{dt}
\]

\[
= {\int }_{0}^{a}{\int }_{{0}^{ - }}^{\infty }\cos \left( {at}\right) {e}^{-{st}}{dtda}
\]

\[
= {\int }_{0}^{a}\mathcal{L}\{ \cos \left( {at}\right) \} {da}
\]

\[
= {\int }_{0}^{a}\frac{s}{{s}^{2} + {a}^{2}}{da}
\]

\[
= {\tan }^{-1}\left( {a/s}\right)
\]


## Teaching Points

1. Parameter integrals can simplify difficult Laplace transforms.
2. Exchanging integration order requires convergence assumptions.
3. Known transform pairs greatly reduce computational complexity.
4. Inverse tangent functions naturally arise from rational integrals.
5. This result is important in frequency-response and signal analysis.
