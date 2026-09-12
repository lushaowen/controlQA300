# Solution

We compute the Laplace transforms by applying linearity and standard transform identities.
Only key steps and methods are highlighted; intermediate algebra is omitted for brevity.

---

## Method

### (a)–(d): Basic Exponentials and Trigonometric Functions

- **(a)** $1 - e^{-t}$
  $$
  \mathcal{L}\{1\} - \mathcal{L}\{e^{-t}\}
  = \frac{1}{s} - \frac{1}{s+1}.
  $$

- **(b)** $e^{-t} - e^{-2t}$
  $$
  \frac{1}{s+1} - \frac{1}{s+2}.
  $$

- **(c)** $\sinh(t) - \cosh(2t)$
  $$
  \frac{1}{s^2-1} - \frac{s}{s^2-4}.
  $$

- **(d)** $\sin(t) - \cos(t)$
  $$
  \frac{1}{s^2+1} - \frac{s}{s^2+1}.
  $$

---

### (e)–(h): Polynomial, Modulated, and Shifted Signals

- **(e)** $t + t e^{-t}$
  $$
  \frac{1}{s^2} + \frac{1}{(s+1)^2}.
  $$

- **(f)** $\sin(t) - e^{-t}\cos(2t)$
  $$
  \frac{1}{s^2+1} - \frac{s+1}{(s+1)^2+4}.
  $$

- **(g)** $t\sin(t) + \cos(2t)$
  $$
  \frac{s}{s^2+4} + \frac{2s}{(s^2+1)^2}.
  $$

- **(h)** $e^{-t}\cos\!\left(t+\frac{\pi}{4}\right)$
  $$
  \frac{s}{\sqrt{2}(s^2+2s+2)}.
  $$

---

### (i)–(l): Step Functions, Impulses, and Polynomials

- **(i)** $1(t) + 1(t-1)$
  $$
  \frac{1}{s} + \frac{e^{-s}}{s}.
  $$

- **(j)** $e^{-t} + 1(t-1)e^{t-1}$
  $$
  \frac{1}{s+1} + \frac{e^{-s}}{s-1}.
  $$

- **(k)** $\delta(t) + t e^{-t}\sin(t)$
  $$
  1 + \frac{2(s+1)}{(s^2+2s+2)^2}.
  $$

- **(l)** $1 + t - t^2$
  $$
  \frac{1}{s} + \frac{1}{s^2} - \frac{2}{s^3}.
  $$

---

## Teaching Points

1. Linearity greatly simplifies Laplace transform computations
2. Exponential terms shift the Laplace variable $s$
3. Polynomial factors correspond to higher-order poles
4. Time shifts introduce exponential multipliers
5. Impulses contribute constant terms in the Laplace domain
6. Grouping by signal type improves efficiency and accuracy
