# Problem
## Problem Description
Show that

\[
\mathop{\lim }\limits_{{\epsilon  \rightarrow  0}}{\int }_{{0}^{ - }}^{t}f\left( {t - \tau }\right) {p}_{\epsilon }\left( \tau \right) {d\tau } = f\left( t\right)
\]

when \( f \) is continuous and differentiable. Hint: Use the mean-value theorem to write \( f\left( t\right)  - f\left( {t - \tau }\right)  = \tau \dot{f}\left( \xi \right) \) , where \( \xi  \in  \left\lbrack  {t - \tau , t}\right\rbrack \) .

## Subproblems
1. Express the integral $\int_{0^{-}}^{t} f(t - \tau) p_{\epsilon}(\tau) d\tau$ using the explicit definition of $p_{\epsilon}(\tau)$ for a sufficiently small $\epsilon$.
2. Apply the Mean-Value Theorem to rewrite the term $f(t - \tau)$ in terms of $f(t)$ and its derivative.
3. Perform the integration with respect to $\tau$ over the interval $[0, \epsilon]$.
4. Evaluate the limit as $\epsilon \rightarrow 0$ to obtain the final result.

## Additional Information
- **Definition of Pulse**: $p_{\epsilon}(\tau) = \epsilon^{-1}$ for $0 \le \tau \le \epsilon$.
- **Mean-Value Theorem Hint**: Use the relation $f(t) - f(t - \tau) = \tau \dot{f}(\xi)$, where $\xi \in [t - \tau, t]$. This can be rearranged as $f(t - \tau) = f(t) - \tau \dot{f}(\xi)$.
- Assume $t > \epsilon > 0$.

## Constraints
- The solution must explicitly use the provided Mean-Value Theorem hint.
- All integration steps must be shown.
- The distinction between variables of integration ($\tau$) and constant parameters ($t$) must be clear.