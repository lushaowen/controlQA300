# Solution

## Method

Assuming zero-initial conditions and applying the Laplace transform

\[
R C_{2} s V_{0}(s) + R C_{1} s V(s) + V(s) = 0
\]

from which

\[
V_{0}(s) = G(s) V(s), \quad
G(s) = \frac{1 + R C_{1} s}{R C_{2} s}
= \frac{C_{1}}{C_{2}} \frac{s + \frac{1}{R C_{1}}}{s}.
\]

This transfer-function is not asymptotically stable because it has a pole at the origin.

## Teaching Points

1. Application of Laplace transforms to linear differential equations.
2. Interpretation of transfer-functions in electrical circuit models.
3. Relationship between pole locations and system stability.
4. Physical meaning of integrator behavior associated with poles at the origin.
5. Importance of zero-initial condition assumptions in system analysis.
