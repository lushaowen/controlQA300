# Solution

## Method

In response to a constant voltage, \( v_{a}(t) = \widetilde{v}_{a} \), the Laplace transform of the angular velocity, \( \Omega(s) \), is:

\[
\Omega(s) = G(s)\frac{\widetilde{v}_{a}}{s}
= \frac{\widetilde{v}}{s}\frac{\beta}{s + \alpha}
\]

Expanding in partial fractions:

\[
\Omega(s) = \widetilde{v}\frac{\beta}{\alpha}
\left( \frac{1}{s} - \frac{1}{s + \alpha} \right)
\]

from which we can identify the transient and steady-state parts of the response:

\[
v_{\text{atr}}(t) = - \widetilde{v}\frac{\beta}{\alpha} e^{-\alpha t},
\]

\[
v_{\text{ass}}(t) = \widetilde{v}\frac{\beta}{\alpha}.
\]

## Teaching Points

1. Step response analysis of first-order electromechanical systems.
2. Use of Laplace transforms to separate transient and steady-state behavior.
3. Interpretation of exponential decay terms as transient responses.
4. Physical meaning of steady-state motor speed under constant voltage.
5. Relationship between system parameters and response speed.
