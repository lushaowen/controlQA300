# Solution

We are asked to show that both the Laplace transform and its inverse are linear operators.

---

## Method

### Step 1: Definition of Linearity

An operator \( L \) is linear if, for any functions \( f_1(t), f_2(t) \) and scalars \( \alpha, \beta \),
\[
L(\alpha f_1 + \beta f_2) = \alpha L(f_1) + \beta L(f_2)
\]

---

### Step 2: Linearity of the Laplace Transform

Consider the Laplace transform of a linear combination of functions:
\[
\mathcal{L}\{\alpha f_1(t) + \beta f_2(t)\}
\]

Using the definition of the Laplace transform:
\[
\mathcal{L}\{\alpha f_1 + \beta f_2\}
= \int_{0}^{\infty} (\alpha f_1(t) + \beta f_2(t)) e^{-st} \, dt
\]

By the linearity of integration:
\[
= \alpha \int_{0}^{\infty} f_1(t)e^{-st} \, dt
+ \beta \int_{0}^{\infty} f_2(t)e^{-st} \, dt
\]

Recognizing each integral as a Laplace transform:
\[
= \alpha \mathcal{L}\{f_1(t)\} + \beta \mathcal{L}\{f_2(t)\}
\]

Thus, the Laplace transform is a linear operator.

---

### Step 3: Linearity of the Inverse Laplace Transform

Let:
\[
F_1(s) = \mathcal{L}\{f_1(t)\}, \quad F_2(s) = \mathcal{L}\{f_2(t)\}
\]

Then:
\[
\mathcal{L}^{-1}\{\alpha F_1(s) + \beta F_2(s)\}
= \alpha \mathcal{L}^{-1}\{F_1(s)\} + \beta \mathcal{L}^{-1}\{F_2(s)\}
\]

This follows directly from the fact that the inverse Laplace transform is defined via linear contour integration in the complex plane, which preserves linearity.

Therefore, the inverse Laplace transform is also linear.

---

## Teaching Points

1. Linearity of transforms follows directly from the linearity of integration.
2. This property allows complex signals to be decomposed into simpler components.
3. Linearity is essential for applying superposition in system analysis.
4. Both forward and inverse transforms preserve linear combinations.
5. This concept underpins transfer-function-based modeling of LTI systems.
