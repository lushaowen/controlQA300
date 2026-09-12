# Problem

## Problem Description
using the PI controller

\[
\tau \left( t\right)  = {K}_{\mathrm{p}}e\left( t\right)  + {K}_{\mathrm{i}}{\int }_{0}^{t}e\left( \sigma \right) {d\sigma },\;e = {\overline{\omega }}_{2} - {\omega }_{2},
\]

and select the gains $ {K}_{\mathrm{p}} $ and $ {K}_{\mathrm{i}} $ such that both closed-loop poles have negative real part more negative than the pole of the machine without performing a pole-zero cancellation. Is the closed-loop capable of asymptotically tracking a constant reference input $ {\overline{\omega }}_{2} $?

## Subproblems
1. Derive the open-loop transfer function from error $e$ to torque $\tau$ for the PI controller and express it in standard form.
2. Determine the loop transfer function $L(s)$ combining the plant $G(s)$ and the PI controller $K(s)$.
3. Identify poles and zeros of the loop transfer function and sketch the qualitative root-locus behavior.
4. Choose the zero location $z = K_i / K_p$ such that it lies to the left of the plant pole $-\alpha$, ensuring improved damping and faster response.
5. Select proportional gain $K_p$ sufficiently large to shift both closed-loop poles further left than $-\alpha$, avoiding any pole-zero cancellation.
6. Analyze whether the system achieves asymptotic tracking of a constant reference signal.

## Additional Information 
- The underlying plant dynamics are unchanged from P6.11: first-order with time constant $1/\alpha$, driven by belt-coupled rotational inertia.
- A PI controller introduces one pole at the origin (integrator) and one finite zero in the left-half plane.
- Root locus starts at open-loop poles ($0, -\alpha$) and ends at zero ($-z$) and infinity; its shape depends critically on the relative position of $z$ and $\alpha$.
- To achieve faster transient response, closed-loop poles must lie deeper in the left half-plane — i.e., with real parts less than $-\alpha$.
- Avoiding pole-zero cancellation ensures robustness and full observability/controllability.

## Constraints
- Do not cancel the plant pole $-\alpha$ with the controller zero.
- All parameter values remain consistent with those given in P6.11.
- Use only root-locus techniques (no frequency response or state-space methods).
- Justify design choices based on root-locus properties such as asymptotes, breakaway points, and angle conditions.
- Final selection of $K_p$ and $K_i$ should be numerically feasible and physically meaningful.
