# Solution

We first prove the general analyticity result, and then verify it for each given
Laplace-domain function.

---

## Method

### General Proof

If \( f(t) = 0 \) for all \( t \ge T \), then its Laplace transform reduces to
\[
F(s) = \int_0^\infty f(t)e^{-st}\,dt = \int_0^T f(t)e^{-st}\,dt.
\]

This is a **definite integral over a finite interval** whose integrand is an entire
function of \( s \). If the integral converges for one value of \( s \), then it converges
for all \( s \in \mathbb{C} \).

Hence, \( F(s) \) is either entire or has only removable singularities arising from
algebraic manipulations.

---

### Removable Singularities via Taylor Expansion

Each function admits a Taylor expansion about its apparent singular point:

- **(a)**  
  \[
  F(s) = 1 - s + O(s^2)
  \]

- **(b)**  
  \[
  F(s) = 1 - \frac{s}{2} + O(s^2)
  \]

- **(c)**  
  \[
  F(s) = s + O(s^2)
  \]

- **(d)**  
  \[
  F(s) = 1 - s + O(s^2)
  \]

- **(e)**  
  \[
  F(s) = 2s + O(s^2)
  \]

- **(f)**  
  \[
  F(s) = 2 - 4s + O(s^2)
  \]

- **(g)**  
  \[
  F(s) = \frac{1}{e} - \frac{s-1}{2e} + O((s-1)^2)
  \]

Thus, all singularities are removable.

---

## Inverse Laplace Transforms

The corresponding time-domain signals are:

- **(a)**  
  \[
  f(t) = \delta(t-2) - \delta(t-1) + \delta(t)
  \]

- **(b)**  
  \[
  f(t) = 1 - 1(t-1)
  \]

- **(c)**  
  \[
  f(t) = 1 - 2\,1(t-1) + 1(t-2)
  \]

- **(d)**  
  \[
  f(t) = t - 2(t-1)1(t-1) + (t-2)1(t-2)
  \]

- **(e)**  
  \[
  f(t) = t - 2(t-1)1(t-1) + 2(t-3)1(t-3) - (t-4)1(t-4)
  \]

- **(f)**  
  \[
  f(t) = t^2 + \frac{1}{2}\Big[-2(t-1)^2 1(t-1)
  +2(t-3)^2 1(t-3)
  -(t-4)^2 1(t-4)\Big]
  \]

- **(g)**  
  \[
  f(t) = -e^{t-1}\big(1(t-1) - 1\big)
  \]

Each signal is identically zero for all \( t \ge T \) for some finite \( T \).

---

## Teaching Points

1. Finite-duration signals have entire Laplace transforms
2. Apparent poles may be removable via series expansion
3. Exponential delays correspond to time shifts
4. Polynomial factors in \( s^{-n} \) yield ramp-like signals
5. Analyticity connects signal support with complex analysis
6. Laplace transforms encode both time-domain support and smoothness
