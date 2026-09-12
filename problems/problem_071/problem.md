# Problem

## Problem Description

Show that

\[
\mathop{\lim }\limits_{{\epsilon  \rightarrow  0}}{\int }_{{0}^{ - }}^{t}f\left( \tau \right) {p}_{\epsilon }\left( \tau \right) {d\tau } = f\left( 0\right) ,
\]

when \( f \) is continuous and differentiable. 

## Subproblems
1. Define the integral limits and substitute the analytical expression of $p_{\epsilon}(\tau)$ into the integral.
2. Use the Mean-Value Theorem to express $f(\tau)$ in terms of $f(0)$ and its derivative $\dot{f}(\xi)$.
3. Perform the integration for both the constant term and the first-order term.
4. Apply the limit $\epsilon \rightarrow 0$ and verify the result.

## Additional Information
- The term $0^{-}$ ensures the inclusion of any potential discontinuity or impulse starting at exactly $\tau = 0$.
- Mean-Value Theorem Hint: For a differentiable function, $f(\tau) - f(0) = \tau \dot{f}(\xi)$ where $\xi \in [0, \tau]$.
- This property is a foundational step in defining the sampling (sifting) property of the Dirac Delta function $\delta(\tau)$.

## Constraints
- All derivation steps involving the Mean-Value Theorem must be explicitly shown.
- Do not rely on external problem references; provide a self-contained proof.
- Clearly identify the behavior of the remainder term as $\epsilon \rightarrow 0$.