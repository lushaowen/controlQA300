# Problem: Laplace Transform of the Unit Pulse Function in the Limit

## Problem Description
Let $p_{\epsilon}(t)$ be a rectangular unit pulse function defined as:
$$
p_{\epsilon}(t) = \begin{cases} \frac{1}{\epsilon}, & 0 \le t \le \epsilon \\ 0, & \text{otherwise} \end{cases}
$$
Show that as the pulse width $\epsilon$ approaches zero, the Laplace transform of $p_{\epsilon}(t)$ approaches unity:
$$
\lim_{\epsilon \rightarrow 0} \mathcal{L}\{p_{\epsilon}(t)\} = 1
$$

## Subproblems
1. Write the integral definition of the Laplace transform for the function $p_{\epsilon}(t)$.
2. Identify the specific function $f(\tau)$ within the Laplace integral that can be evaluated using the sampling property of the unit pulse.
3. Apply the sampling property $\lim_{\epsilon \rightarrow 0} \int_{0^{-}}^{\infty} f(\tau) p_{\epsilon}(\tau) d\tau = f(0)$ to find the limit.
4. Interpret the result in the context of the Dirac Delta function $\delta(t)$.

## Additional Information
- The Laplace transform is defined as $\mathcal{L}\{g(t)\} = \int_{0^{-}}^{\infty} g(t) e^{-st} dt$.
- Recall the sampling property: for any continuous function $f(t)$, the integral of its product with a unit pulse $p_{\epsilon}(t)$ over $[0, \epsilon]$ converges to $f(0)$ as $\epsilon \to 0$.
- Assume $s$ is a complex frequency variable.

## Constraints
- The derivation must start from the integral definition of the Laplace transform.
- Use the sampling property of pulses to evaluate the limit.
- Clearly state the evaluation of the exponential term at $t=0$.