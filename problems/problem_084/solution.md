# Solution

## Method

In order to convert the line integral to the contour integral we need to establish with \( s = \rho {e}^{j\theta } \) that

\[
\left| {{\int }_{{C}^{\rho }}G\left( {-s}\right) G\left( s\right) {ds}}\right|  = \left| {{\int }_{\pi /2}^{{3\pi }/2}G\left( {-\rho {e}^{j\theta }}\right) G\left( {\rho {e}^{j\theta }}\right) \rho {e}^{j\theta }{d\theta }}\right|
\]

\[
\leq  {\int }_{\pi /2}^{{3\pi }/2}{\rho G}\left( {-\rho {e}^{j\theta }}\right) G\left( {\rho {e}^{j\theta }}\right) {d\theta }
\]

As 

\[
\left| {{\int }_{{\mathcal{C}}_{ - }^{\rho }}G\left( {-s}\right) G\left( s\right) {ds}}\right|  \leq  {\int }_{\pi /2}^{{3\pi }/2}\frac{\rho {M}^{2}}{{\left| \rho {e}^{j\theta }\right| }^{2k}}{d\theta }
\]

\[
\leq  \frac{{M}^{2}}{{\rho }^{{2k} - 1}}{\int }_{\pi /2}^{{3\pi }/2}{d\theta } = \frac{\pi {M}^{2}}{{\rho }^{{2k} - 1}}
\]

so that for \( k \geq  1 \)

\[
\mathop{\lim }\limits_{{\rho  \rightarrow  \infty }}\left| {{\int }_{{C}_{ - }^{\rho }}G\left( {-s}\right) G\left( s\right) {ds}}\right|  \leq  \mathop{\lim }\limits_{{\rho  \rightarrow  \infty }}\frac{\pi {M}^{2}}{{\rho }^{{2k} - 1}} = 0.
\]

We now calculate

\[
\parallel G{\parallel }_{2}^{2} = \frac{1}{2\pi j}{\int }_{{\Gamma }_{ - }^{0}}G\left( {-s}\right) G\left( s\right) {ds} = \mathop{\sum }\limits_{k}{\operatorname{Res}}_{s = {s}_{k}}G\left( {-s}\right) G\left( s\right)
\]

where \( {s}_{k} \) are poles with negative real part. For \( G\left( s\right)  = {\left( s + a\right) }^{-1} \) and \( a > 0 \) the only such pole is \( s =  - a \) so that

\[
\parallel G{\parallel }_{2}^{2} = \mathop{\lim }\limits_{{s \rightarrow   - 1}}\left( {s + a}\right) {\left( -s + a\right) }^{-1}{\left( s + a\right) }^{-1} = \mathop{\lim }\limits_{{s \rightarrow   - a}}\frac{1}{-s + a} = \frac{1}{2a}.
\]

## Teaching Points

1. The $L_2$ norm admits equivalent time-, frequency-, and complex-domain representations
2. Asymptotic stability ensures convergence of contour integrals
3. Decay conditions guarantee vanishing arc contributions
4. Residue theory provides an efficient computational tool
5. Simple first-order systems yield closed-form norm expressions
