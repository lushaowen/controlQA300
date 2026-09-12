# Problem: Final Value of the Integral of sin(at)/t

## Problem Description

Use properties of the Laplace transform to evaluate the long-time limit of the integral

$$
\int_{0^-}^{t} \frac{\sin(at)}{t}\, dt.
$$

Specifically,, together with the time integration property and the final value theorem of the Laplace transform, to show that

$$
\lim_{t \to \infty} \int_{0^-}^{t} \frac{\sin(at)}{t}\, dt
= \operatorname{sign}(a)\,\frac{\pi}{2}.
$$

---

## Subproblems

1. Recall the Laplace transform of \( \sin(at)/t \) from Problem 3.9.
2. Apply the time integration property of the Laplace transform.
3. Compute the Laplace transform of the integral \( \int_{0^-}^{t} \frac{\sin(at)}{t}\, dt \).
4. Apply the final value theorem.
5. Evaluate the resulting limit as \( s \to 0 \).

---

## Additional Information

- Assume \( a \neq 0 \) and \( \Re(s) > 0 \).
- You may assume the final value theorem is applicable.
- The sign function is defined as
  \[
  \operatorname{sign}(a)=
  \begin{cases}
  1, & a>0, \\
  -1, & a<0.
  \end{cases}
  \]

---

## Constraints

- All steps must be clearly justified.
- The use of Laplace transform properties must be explicit.
- Limits must be evaluated analytically.
