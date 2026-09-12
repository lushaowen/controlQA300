# Solution

## Method
To find a suitable pulse function, we use polynomial construction. We enforce the boundary conditions to determine the functional form and then apply the normalization constraint $\int p(t) dt = 1$ to solve for the leading coefficient $a$.

---

## Step 1: Second-Order Polynomial Pulse

To satisfy $p(0) = 0$ and $p(2\epsilon) = 0$, the simplest polynomial form is:
$$p(t) = at(2\epsilon - t), \quad a > 0$$
This is a downward-opening parabola.

To find $a$, we enforce the unit area constraint:
$$\int_{0}^{2\epsilon} at(2\epsilon - t) dt = 1$$
Expanding the integrand:
$$a \int_{0}^{2\epsilon} (2\epsilon t - t^2) dt = a \left[ \epsilon t^2 - \frac{t^3}{3} \right]_{0}^{2\epsilon}$$
Substituting the limits:
$$a \left( \epsilon(2\epsilon)^2 - \frac{(2\epsilon)^3}{3} \right) = a \left( 4\epsilon^3 - \frac{8\epsilon^3}{3} \right) = a \left( \frac{12\epsilon^3 - 8\epsilon^3}{3} \right) = \frac{4}{3}a\epsilon^3$$
Setting this equal to 1:
$$\frac{4}{3}a\epsilon^3 = 1 \implies a = \frac{3}{4\epsilon^3}$$

The resulting pulse is:
$$p(t) = \frac{3}{4\epsilon^3} t(2\epsilon - t)$$

---

## Step 2: Fourth-Order Differentiable Pulse

For a pulse to be everywhere differentiable, including the points where it meets the zero-line at $t=0$ and $t=2\epsilon$, we require $p(0)=p(2\epsilon)=0$ and $\dot{p}(0)=\dot{p}(2\epsilon)=0$.
This suggests a polynomial with repeated roots at $0$ and $2\epsilon$:
$$p(t) = a t^2 (2\epsilon - t)^2$$

To find $a$, we integrate:
$$\int_{0}^{2\epsilon} a t^2 (2\epsilon - t)^2 dt = 1$$
Expanding the square: $(2\epsilon - t)^2 = 4\epsilon^2 - 4\epsilon t + t^2$.
$$a \int_{0}^{2\epsilon} (4\epsilon^2 t^2 - 4\epsilon t^3 + t^4) dt = a \left[ \frac{4\epsilon^2 t^3}{3} - \epsilon t^4 + \frac{t^5}{5} \right]_{0}^{2\epsilon}$$
Substituting $t = 2\epsilon$:
$$a \left( \frac{4\epsilon^2 (8\epsilon^3)}{3} - \epsilon (16\epsilon^4) + \frac{32\epsilon^5}{5} \right) = a \epsilon^5 \left( \frac{32}{3} - 16 + \frac{32}{5} \right)$$
Finding a common denominator (15):
$$a \epsilon^5 \left( \frac{160 - 240 + 96}{15} \right) = a \epsilon^5 \left( \frac{16}{15} \right)$$
Setting this equal to 1:
$$\frac{16}{15} a \epsilon^5 = 1 \implies a = \frac{15}{16\epsilon^5}$$

The resulting smooth pulse is:
$$p(t) = \frac{15}{16\epsilon^5} t^2 (2\epsilon - t)^2$$

---

## Teaching Points
1. **Pulse Approximation**: Approximating a delta function requires the integral of the pulse to be exactly 1 as the width $2\epsilon$ approaches zero.
2. **Smoothness Requirements**: Piecewise linear pulses (like triangles) have discontinuous derivatives. Higher-order polynomials allow for $C^1$ or higher continuity.
3. **Boundary Conditions**: Repeated roots in a polynomial construction automatically satisfy zero-value and zero-derivative conditions at the boundaries.
4. **Scaling**: The amplitude of the pulse must scale inversely with $\epsilon$ (specifically $\epsilon^{-3}$ or $\epsilon^{-5}$) to maintain constant area as the pulse narrows.