# Problem: Laplace Transforms of Elementary and Composite 


## Problem Description

Compute the Laplace transform of the following time-domain signals $f(t)$ defined for $t \ge 0$.
Each signal involves combinations of elementary functions such as exponentials, polynomials,
trigonometric functions, hyperbolic functions, step functions, and impulses.

The goal is to apply standard Laplace transform properties, including linearity, time shifting,
frequency shifting, and differentiation with respect to $s$.

---

## Subproblems

Compute $\mathcal{L}\{f(t)\}$ for each of the following:

**(a)** $1 - e^{-t}$  
**(b)** $e^{-t} - e^{-2t}$  
**(c)** $\sinh(t) - \cosh(2t)$  
**(d)** $\sin(t) - \cos(t)$  

**(e)** $t + t e^{-t}$  
**(f)** $\sin(t) - e^{-t}\cos(2t)$  
**(g)** $t\sin(t) + \cos(2t)$  
**(h)** $e^{-t}\cos\!\left(t + \frac{\pi}{4}\right)$  

**(i)** $1(t) + 1(t-1)$  
**(j)** $e^{-t} + 1(t-1)e^{t-1}$  
**(k)** $\delta(t) + t e^{-t}\sin(t)$  
**(l)** $1 + t - t^2$

---

## Additional Information

- All signals are causal unless explicitly shifted.
- $1(t)$ denotes the unit step function.
- $\delta(t)$ denotes the Dirac delta distribution.
- You may use standard Laplace transform tables.
- The Laplace transform is defined as
  $$
  \mathcal{L}\{f(t)\} = \int_0^\infty f(t)e^{-st}\,dt.
  $$

---

## Constraints

- Use linearity whenever possible.
- Clearly apply time-shift and frequency-shift properties.
- Final answers should be expressed as rational functions of $s$.
- No inverse transforms are required.
