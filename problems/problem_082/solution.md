# Solution

## Method

With \( s = \alpha  + \rho {e}^{j\theta } = \alpha  + \rho \cos \theta  + {j\rho }\sin \theta \) :

\[
\left| {{\int }_{{C}_{ + }^{\rho }}F\left( s\right) {e}^{st}{ds}}\right|  \leq  \left| {{\int }_{\pi /2}^{-\pi /2}F\left( {\alpha  + \rho {e}^{j\theta }}\right) {e}^{\left( {\alpha  + \rho {e}^{j\theta }}\right) t}{j\rho }{e}^{j\theta }{d\theta }}\right|
\]

Using P3.28 and \( \rho  > 0 \)

\[
\left| {{\int }_{{C}_{ + }^{\rho }}F\left( s\right) {e}^{st}{ds}}\right|  \leq  \rho {\int }_{-\pi /2}^{\pi /2}\left| {F\left( {\alpha  + \rho {e}^{j\theta }}\right) {e}^{\left( {\alpha  + \rho {e}^{j\theta }}\right) t}}\right| {d\theta },
\]

\[
\leq  \frac{{\rho M}{e}^{\alpha t}}{{\left( \rho  - \left| \alpha \right| \right) }^{k}}{\int }_{-\pi /2}^{\pi /2}{e}^{{\rho t}\cos \theta }{d\theta }.
\]

Using P3.27 and \( t < 0 \)

\[
\left| {{\int }_{{C}_{ + }^{\rho }}F\left( s\right) {e}^{st}{ds}}\right|  \leq  \frac{{\rho M}{e}^{\alpha t}}{{\left( \rho  - \left| \alpha \right| \right) }^{k}}{\int }_{-\pi /2}^{\pi /2}{e}^{{\rho t}\cos \theta }{d\theta } \leq  \frac{{\rho M}{e}^{\alpha t}}{{\left( \rho  - \left| \alpha \right| \right) }^{k}}\frac{\pi }{\rho \left| t\right| } = \frac{{\pi M}{e}^{\alpha t}}{\left| t\right| {\left( \rho  - \left| \alpha \right| \right) }^{k}}
\]

Therefore, for any given \( t < 0 \) the quantity \( \frac{{\pi M}{e}^{\alpha t}}{\left| t\right| } \) is bounded and therefore

\[
\mathop{\lim }\limits_{{\rho  \rightarrow  \infty }}\left| {{\int }_{{C}_{ + }^{\rho }}F\left( s\right) {e}^{st}{ds}}\right|  \leq  \mathop{\lim }\limits_{{\rho  \rightarrow  \infty }}\frac{{\pi M}{e}^{\alpha t}}{\left| t\right| {\left( \rho  - \left| \alpha \right| \right) }^{k}} = 0.
\]


## Teaching Points
1. **Jordan's Lemma Variant**: This proof is a variation of Jordan's Lemma, applied to a right-half plane contour and negative time $t < 0$.
2. **Impact of Sign of $t$**: It is crucial to observe how $t < 0$ allows us to form a positive $R$ for the exponential decay term $e^{-R \cos \theta}$, ensuring convergence.
3. **Integral Estimation Technique**: Moving the absolute value inside the integral (ML-inequality logic) is the standard starting point for proving the vanishing of contour integrals.
4. **Prerequisite Integration**: This problem demonstrates how complex proofs are built incrementally from simpler inequalities (like the linear bound for $\cos \theta$).