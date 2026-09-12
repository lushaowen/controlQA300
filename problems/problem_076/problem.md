# Problem
## Problem Description

Show that

\[
\mathop{\lim }\limits_{{\epsilon  \rightarrow  0}}{\int }_{{0}^{ - }}^{t}f\left( {t - \tau }\right) {\dot{p}}_{\epsilon }\left( \tau \right) {d\tau } = \dot{f}\left( t\right) ,
\]

when \( f \) is continuous and differentiable. Hint: Apply the mean-value theorem on each segment where \( {\dot{p}}_{\epsilon }\left( t\right) \) is not zero.

## Subproblems
1. Partition the integral into two segments based on the definition of $\dot{p}_{\epsilon}(\tau)$.
2. Use the Mean-Value Theorem (MVT) to approximate $f(t-\tau)$ around the point $t$.
3. Evaluate the integrals of the constant term and the first-order term across both segments.
4. Apply the limit $\epsilon \rightarrow 0$ and justify why the result converges to $\dot{f}(t)$.

## Additional Information
- **Mean-Value Theorem Hint**: For small $\tau$, express $f(t-\tau) = f(t) - \tau \dot{f}(\xi)$, where $\xi \in [t-\tau, t]$.
- The pulse $p_{\epsilon}(t)$ is a continuous triangular function with peak height $1/\epsilon$ at $t=\epsilon$, starting from $0$ at $t=0$ and ending at $0$ at $t=2\epsilon$.
- As $\epsilon \to 0$, the interval $[t-2\epsilon, t]$ shrinks to the point $t$, implying $\xi \to t$.

## Constraints
- All derivation steps involving the integral segments must be shown.
- Use the provided MVT substitution.
- Clearly demonstrate how the $f(t)$ terms cancel out.