# Solution

## Method

With \( s = \alpha  + \rho {e}^{j\theta } = \alpha  + \rho \cos \theta  + {j\rho }\sin \theta ,\rho  > 0 \) :

\[
\left| {F\left( s\right) {e}^{st}}\right|  = \left| {F\left( s\right) }\right| {e}^{\left( {\alpha  + \rho \cos \theta }\right) t} \leq  \frac{M{e}^{\alpha t}}{{\left| \alpha  + \rho {e}^{j\theta }\right| }^{k}}{e}^{{\rho t}\cos \theta }
\]

after using (3.26). Using the hint

\[
\left| {\alpha  + \rho {e}^{j\theta }}\right|  \geq  \rho \left| {e}^{j\theta }\right|  - \left| \alpha \right|  = \rho  - \left| \alpha \right|
\]

so that

\[
\left| {F\left( s\right) {e}^{st}}\right|  \leq  \frac{M{e}^{\alpha t}}{{\left| \alpha  + \rho {e}^{j\theta }\right| }^{k}}{e}^{{\rho t}\cos \theta } \leq  \frac{M{e}^{\alpha t}}{{\left( \rho  - \left| \alpha \right| \right) }^{k}}{e}^{{\rho t}\cos \theta }.
\]

## Teaching Points
1. **Magnitude of Complex Exponentials**: Students must remember that only the real part of the exponent contributes to the magnitude ($|e^{a+jb}| = e^a$).
2. **Reverse Triangle Inequality**: This is a crucial tool for finding upper bounds of fractions by finding the minimum possible value of the denominator.
3. **Contour Parametrization**: Understanding how to shift a standard polar coordinate system by a real value $\alpha$.
4. **Asymptotic Behavior**: This type of estimation is a fundamental step in proving that the integral over a large arc vanishes in the context of the Inverse Laplace Transform (related to Jordan's Lemma).