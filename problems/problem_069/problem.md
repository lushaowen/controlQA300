# Problem

## Problem Description
Show that

\[
{\int }_{{0}^{ - }}^{\infty }{p}_{\epsilon }\left( \tau \right) {d\tau } = \mathop{\lim }\limits_{{\epsilon  \rightarrow  0}}{\int }_{{0}^{ - }}^{\epsilon }{p}_{\epsilon }\left( \tau \right) {d\tau } = 1.
\]


## Subproblems
1. Define the analytical expression for the pulse function $p_{\epsilon}(\tau)$.
2. Evaluate the definite integral $\int_{0^{-}}^{\infty} p_{\epsilon}(\tau) d\tau$ for a finite $\epsilon > 0$.
3. Evaluate the definite integral $\int_{0^{-}}^{\epsilon} p_{\epsilon}(\tau) d\tau$ and show it is independent of $\epsilon$.
4. Apply the limit $\epsilon \to 0$ to the integral and interpret the result in the context of the unit impulse function.

## Additional Information
- The notation $0^{-}$ denotes the limit from the left, ensuring the inclusion of the discontinuity at the origin.
- The function $p_{\epsilon}(\tau)$ is typically defined as:
  $$
  p_{\epsilon}(\tau) = \begin{cases} \frac{1}{\epsilon}, & 0 \le \tau \le \epsilon \\ 0, & \text{otherwise} \end{cases}
  $$
- This property is fundamental to the definition of the Dirac Delta function $\delta(t)$.

## Constraints
- All steps of the integration must be explicitly shown.
- Use precise limit notation.
- Assume $\epsilon > 0$ during the derivation before taking the limit.