# Problem

## Problem Description

Let \( G\left( s\right) \) be asymptotically stable and satisfying (3.23). Show that

\[
\parallel G{\parallel }_{2}^{2} = \frac{1}{2\pi }{\int }_{-\infty }^{\infty }\left| {G\left( {j\omega }\right) }\right| {d\omega } = \frac{1}{2\pi j}\mathop{\lim }\limits_{{\rho  \rightarrow  \infty }}{\int }_{{\Gamma }_{ - }^{0}}G\left( {-s}\right) G\left( s\right) {ds}
\]

where \( {\Gamma }_{ - }^{0} \) is the contour \( {\Gamma }_{ - }^{\alpha } \) from Fig. 3.2 with \( \alpha  = 0 \) . Explain how to compute this integral using Cauchy's residue theorem (Theorem 3.1). Use this method to verify that

\[
\parallel G{\parallel }_{2}^{2} = \frac{1}{2a}
\]

when \( G\left( s\right)  = {\left( s + a\right) }^{-1} \) .

\[F_1 = \lim_{|s| \to \infty} F(s).\]  
(3.32)
![](images\image.png)
Fig3.2
## Subproblems

1. Show how the frequency-domain expression of $\|G\|_2^2$ can be written as a contour integral.
2. Prove that the contribution from the infinite semicircular arc vanishes as $\rho \to \infty$.
3. Identify the poles of $G(-s)G(s)$ inside the contour $\Gamma_-^0$.
4. Use Cauchy’s residue theorem to evaluate the contour integral.
5. Apply the method to the specific transfer function $G(s) = (s+a)^{-1}$.

---

## Additional Information

- The $L_2$ norm of a transfer function is defined by
  $$
  \|G\|_2^2 = \int_{0^-}^{\infty} g^2(t)\, dt
  $$
  where $g(t)$ is the impulse response.
- Asymptotic stability implies all poles of $G(s)$ lie strictly in the left half-plane.
- You may assume standard results from complex analysis regarding contour integration.

---

## Constraints

- All steps must be justified analytically.
- Clearly state the assumptions required for applying residue theory.
- Limits involving $\rho \to \infty$ must be explicitly evaluated.
- Use standard notation from control theory and complex analysis.
