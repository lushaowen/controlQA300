# Problem

## Problem Description

Let \( u\left( t\right) , t \geq  0 \) , be such that \( u\left( t\right)  = 0 \) for all \( t \geq  T \) and let \( U\left( s\right) \) be its Laplace transform. Show that

\[
y\left( t\right)  = {\mathcal{L}}^{-1}\{ Y\left( s\right) \} ,\;Y\left( s\right)  = \frac{U\left( s\right) }{1 - {e}^{-{sT}}},
\]

is a periodic function with period \( T \) . Use this fact to calculate and sketch the plot of the inverse Laplace transform of

\[
Y\left( t\right)  = \frac{1 - {e}^{-{sT}/2}}{s\left( {1 - {e}^{-{sT}}}\right) }.
\]

Explain what happens when \( u\left( t\right)  \neq  0, t \geq  T \) . Repeat for

\[
Y\left( t\right)  = \frac{1 - {e}^{-{s3T}/2}}{s\left( {1 - {e}^{-{sT}}}\right) }.
\]

## Subproblems
1. Show that \( y(t) \) is a periodic function with period \( T \).
2. Using this result, compute and sketch the inverse Laplace transform of
   \[
   Y(s) = \frac{1 - e^{-sT/2}}{s(1 - e^{-sT})}.
   \]
3. Explain the time-domain structure of the resulting signal.
4. Explain what happens when \( u(t) \neq 0 \) for some \( t \ge T \).
5. Repeat the analysis for
   \[
   Y(s) = \frac{1 - e^{-3sT/2}}{s(1 - e^{-sT})}.
   \]

---

## Additional Information
- Recall the geometric series expansion:
  \[
  \frac{1}{1 - x} = 1 + x + x^2 + \cdots, \quad |x| < 1.
  \]
- The Laplace transform time-shift property states:
  \[
  \mathcal{L}^{-1}\{e^{-skT}U(s)\} = u(t - kT).
  \]
- Assume all transforms exist in the region of convergence.

---

## Constraints
- Periodicity must be demonstrated analytically.
- The inverse Laplace transform must be expressed explicitly in the time domain.
- Sketches should be described clearly using analytical signal descriptions.
- Overlap effects between shifted signals must be explicitly discussed.
