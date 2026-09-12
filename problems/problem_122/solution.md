# Solution

## Method

Assuming zero-initial conditions and applying the Laplace transform

from which

\[
\Omega(s) = G(s) V_a(s), \quad
G(s) = \frac{\frac{K_t}{R_a}}{J s + b + \frac{K_t K_e}{R_a}}
= \frac{\frac{K_t}{R_a J}}{s + \frac{b}{J} + \frac{K_t K_e}{R_a J}}
= \frac{\beta}{s + \alpha},
\quad
\beta = \frac{K_t}{R_a J},
\quad
\alpha = \frac{b}{J} + \frac{K_t K_e}{R_a J}.
\]

If all constants are positive this transfer-function is asymptotically stable.

## Teaching Points

1. Modeling of DC motor dynamics using simplified differential equations.
2. Derivation of transfer-functions from mechanical system models.
3. Interpretation of first-order system poles and stability.
4. Relationship between angular velocity and angular position in the Laplace domain.
5. Physical meaning of damping and electrical back-emf in motor stability.
