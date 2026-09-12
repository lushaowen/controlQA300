# Problem: Analysis of LTI Systems from Impulse Responses

## Problem Description
Repeat the system analysis performed for a first-order LTI system with a unit step input, but now for a variety of impulse responses.

For each impulse response listed below, determine the corresponding transfer function, analyze the system order and stability, and compute the response to a constant input
\[
u(t) = 1, \quad t \ge 0,
\]
assuming zero initial conditions.

The output response should be decomposed into transient and steady-state components.

---

## Subproblems
For each impulse response \( g(t) \), perform the following tasks:
1. Compute the transfer function \( G(s) = \mathcal{L}\{g(t)\} \)
2. Determine the system order from the poles of \( G(s) \)
3. Analyze asymptotic stability
4. Compute the output response \( y(t) \) to a unit step input
5. Identify the transient component \( y_{\mathrm{tr}}(t) \)
6. Identify the steady-state component \( y_{\mathrm{ss}}(t) \)

The impulse responses are:

(a) \( g(t) = e^{-2t} - e^{-t} \)

(b) \( g(t) = e^{t} - e^{-t} \)

(c) \( g(t) = -t e^{-2t} \)

(d) \( g(t) = e^{-t}\cos(t) \)

(e) \( g(t) = e^{-t}(\cos t - \sin t) \)

(f) \( g(t) = \cos(t + \pi/6) \)

(g) \( g(t) = t\cos(t) \)

(h) \( g(t) = \delta(t) + t e^{-t}\sin(t) \)

(i) \( g(t) = 1(t) - 1(t - 1) \)

(j) \( g(t) = t - 2(t - 1)1(t - 1) + (t - 2)1(t - 2) \)

---

## Additional Information
- The transfer function is defined as the Laplace transform of the impulse response.
- A system is asymptotically stable if all poles of \( G(s) \) have strictly negative real parts, or equivalently if
  \[
  \int_0^\infty |g(t)|\,dt < \infty.
  \]
- The unit step input has Laplace transform \( 1/s \).
- The output is given by \( Y(s) = G(s)/s \).

---

## Constraints
- All Laplace-domain expressions must be explicitly stated.
- Pole locations must be identified and interpreted.
- Stability must be justified analytically.
- Transient and steady-state terms must be clearly separated.
