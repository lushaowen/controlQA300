# Problem: Contour Integrals Using Cauchy’s Residue Theorem

## Problem Description
Let \( C \) be the unit circle in the complex plane, centered at the origin and traversed in the counter-clockwise direction.

Evaluate the contour integral
\[
\int_{C} f(s)\, ds
\]
using **Cauchy’s Residue Theorem** for each of the following complex-valued functions.

The objective is to identify the singularities of each function, determine which poles lie inside the unit circle, compute the corresponding residues, and evaluate the contour integrals accordingly.

---

## Subproblems
Evaluate the contour integral for each function:

1. (a) \( f(s) = 1 - e^{-s} \)
2. (b) \( f(s) = \dfrac{1 + e^{-s}}{s} \)
3. (c) \( f(s) = \dfrac{1}{s^2} \)
4. (d) \( f(s) = \dfrac{1}{s(s + \tfrac{1}{2})} \)
5. (e) \( f(s) = \dfrac{s}{(s + \tfrac{1}{2})(s + 2)} \)
6. (f) \( f(s) = \dfrac{1}{s(s + \tfrac{1}{2})} \)
7. (g) \( f(s) = \dfrac{1}{s^2 + \tfrac{1}{4}} \)

---

## Additional Information
- The unit circle is defined by \( |s| = 1 \).
- Cauchy’s Residue Theorem states:
  \[
  \int_{C} f(s)\, ds = 2\pi j \sum \text{Res}(f, s_k)
  \]
  where the sum is taken over all poles \( s_k \) inside \( C \).
- Only isolated singularities contribute to the integral.
- Entire functions have no poles and therefore zero contour integral over closed curves.

---

## Constraints
- Use residue theory explicitly; direct parameterization of the contour is not allowed.
- All poles must be classified (location and order).
- Only residues of poles **inside the unit circle** should be included.
- Final answers must be expressed in terms of \( \pi j \).
