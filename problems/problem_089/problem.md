# Problem: Analyticity and Removable Singularities of Laplace Transforms with Finite Support

## Problem Description

Prove that if a time-domain function \( f(t) \), defined for \( t \ge 0 \), satisfies
\[
f(t) = 0, \quad \forall t \ge T,
\]
for some finite \( T > 0 \), then its Laplace transform
\[
F(s) = \mathcal{L}\{f(t)\}
\]
is an **entire function** in the complex plane \( \mathbb{C} \), or else any singularities
it possesses are **removable singularities**.

After establishing the general result, verify it explicitly for several given Laplace-domain
functions by:

1. Showing that their apparent singularities are removable using Taylor expansions.
2. Computing the inverse Laplace transform \( f(t) \).
3. Verifying that the resulting time-domain functions have finite support.
4. Sketching the qualitative behavior of \( f(t) \) for \( t \ge 0 \).

---

## Subproblems

Verify that the following functions have **only removable singularities**, and compute
their inverse Laplace transforms.

### (a)
\[
F(s) = 1 - e^{-s} + e^{-2s}
\]

### (b)
\[
F(s) = \frac{1 - e^{-s}}{s}
\]

### (c)
\[
F(s) = \frac{1 - 2e^{-s} + e^{-2s}}{s}
\]

### (d)
\[
F(s) = \frac{1 - 2e^{-s} + e^{-2s}}{s^2}
\]

### (e)
\[
F(s) = \frac{1 - 2e^{-s} + 2e^{-3s} - e^{-4s}}{s^2}
\]

### (f)
\[
F(s) = \frac{1 - 2e^{-s} + 2e^{-3s} - e^{-4s}}{s^3}
\]

### (g)
\[
F(s) = \frac{e^{-s-1}(e^s - e)}{s - 1}
\]

---

## Additional Information

- All Laplace transforms are assumed to be one-sided
- A singularity at \( s = s_0 \) is **removable** if:
  - \( \lim_{s \to s_0} F(s) \) exists and is finite
  - All derivatives of \( F(s) \) exist at \( s_0 \)
- A sufficient condition for removability is the existence of a Taylor series expansion
  about the singular point
- The unit step function is denoted by \( 1(t) \), and the Dirac delta by \( \delta(t) \)

---

## Constraints

- The analyticity argument must rely on properties of definite integrals
- Singularities must be analyzed using series expansions
- Inverse Laplace transforms must be computed analytically
- Sketches may be qualitative but must reflect finite support
