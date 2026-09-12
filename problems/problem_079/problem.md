# Problem: Design of Continuous and Differentiable Approximation Pulses

## Problem Description
In signal processing and system analysis, the Dirac delta function $\delta(t)$ is often approximated by a pulse function $p_{\epsilon}(t)$ with a short duration $2\epsilon$ and a total area of unity. While triangular or rectangular pulses are common, they lack differentiability at certain points.

The goal of this problem is to replace a standard pulse with a higher-order polynomial function $p(t)$ that is not only continuous but also differentiable, satisfying specific boundary and normalization conditions. Specifically, we seek a pulse defined on the interval $[0, 2\epsilon]$ such that:
1. It starts and ends at zero: $p(0) = 0, p(2\epsilon) = 0$.
2. It has a positive peak at the midpoint: $p(\epsilon) > 0$.
3. It is smooth at the peak: $\dot{p}(\epsilon) = 0$.
4. It satisfies the normalization property: $\int_{0}^{2\epsilon} p(t) dt = 1$.

## Subproblems
1. Construct a second-order polynomial pulse $p(t)$ that satisfies the boundary conditions at $t=0$ and $t=2\epsilon$, and determine the scaling constant $a$ such that the integral of the pulse is unity.
2. Determine the peak value of this second-order pulse at $t=\epsilon$.
3. Construct a fourth-order polynomial pulse that is "everywhere differentiable" (i.e., its derivative at the boundaries $t=0$ and $t=2\epsilon$ is also zero) and determine its scaling constant $a$ for unit area.
4. Compare the smoothness of the second-order and fourth-order approximations.

## Additional Information
- The pulse is assumed to be zero outside the interval $[0, 2\epsilon]$.
- For the fourth-order pulse to be "smoothly" connected to the zero-signal outside the interval, the derivatives at the boundaries should ideally be zero: $\dot{p}(0) = \dot{p}(2\epsilon) = 0$.

## Constraints
- All derivation steps for the normalization constant $a$ must be shown using definite integrals.
- Use analytical methods for polynomial construction.
- Ensure the resulting functions are expressed in terms of $t$ and the parameter $\epsilon$.