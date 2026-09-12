# Problem

## Problem Description
Calculate (6.15) and (6.16).
$$
H(s) = \frac{K_{\mathrm{p}} N_{L}(s)}{D_{L}(s) + \bigl(K_{\mathrm{p}} + K_{\mathrm{d}} s\bigr) N_{L}(s)}
\tag{6.15}
$$

$$
H(s) = \frac{\bigl(K_{\mathrm{p}} + K_{\mathrm{d}} s\bigr) N_{L}(s)}{D_{L}(s) + \bigl(K_{\mathrm{p}} + K_{\mathrm{d}} s\bigr) N_{L}(s)}
\tag{6.16}
$$


## Subproblems
1. Derive the closed-loop transfer function `H` for the system described by equation (6.15), starting from the definition of the modified plant `\widetilde{G}`.
2. Simplify the expression for `H` in (6.15) to obtain a rational function in terms of the original plant numerator `N_L` and denominator `D_L`.
3. Derive the closed-loop transfer function `H` for the system described by equation (6.16) directly from its block-diagram representation.
4. Simplify the expression for `H` in (6.16) to obtain a rational function in terms of `N_L` and `D_L`, and compare its structure with the result from (6.15).

## Additional Information
- Equations (6.15) and (6.16) refer to the closed-loop transfer functions of two related control system configurations, likely involving a Proportional-Derivative (PD) controller.
- `G` represents the open-loop transfer function (plant) and can be expressed as `G = N_L / D_L`.
- `K_p` and `K_d` are the proportional and derivative gains of the controller, respectively.
- The variable `s` is the complex frequency variable from the Laplace transform.

## Constraints
- Algebraic manipulations must be shown step-by-step.
- The final answer for each equation must be expressed as a single rational function.
- Assume `G`, `N_L`, and `D_L` are proper rational functions of `s`.