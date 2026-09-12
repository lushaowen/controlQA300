# Problem

## Problem Description

A linear time-invariant system has as impulse response

\[
g\left( t\right)  = {e}^{-t},\;t \geq  0.
\]

Compute the system's transfer-function. What is the order of the system? Is the system asymptotically stable? Assuming zero initial conditions, calculate and sketch the response to a constant input \( u\left( t\right)  = 1, t \geq  0 \) . Identify the transient and steady-state components of the response.


## Subproblems
1. Compute the transfer function \( G(s) \) of the system.
2. Determine the order of the system.
3. Assess whether the system is asymptotically stable.
4. Assuming zero initial conditions, compute the system response to the constant input
   \[
   u(t) = 1, \quad t \ge 0.
   \]
5. Sketch the output response \( y(t) \).
6. Decompose the response into transient and steady-state components.

---

## Additional Information
- The transfer function is defined as the Laplace transform of the impulse response:
  \[
  G(s) = \mathcal{L}\{g(t)\}.
  \]
- The Laplace transform of the unit step function is:
  \[
  \mathcal{L}\{1\} = \frac{1}{s}.
  \]
- A system is asymptotically stable if all poles of \( G(s) \) lie strictly in the left half-plane.
- Zero initial conditions are assumed throughout the analysis.

---

## Constraints
- All Laplace transforms and inverse transforms must be shown explicitly.
- Stability must be justified using pole locations.
- The response must be expressed analytically before being interpreted graphically.
- Transient and steady-state terms must be clearly identified.
