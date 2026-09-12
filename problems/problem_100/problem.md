# Problem
## Problem Description
Consider a rotating machine driven by a belt without slip, as described by the following ordinary differential equation (ODE):
$$(J_1 r_2^2 + J_2 r_1^2) \dot{\omega}_1 + (b_1 r_2^2 + b_2 r_1^2) \omega_1 = r_2^2 \tau$$
where:
- $\omega_1$ is the angular velocity of the driving shaft.
- $\omega_2$ is the angular velocity of the machine, related to $\omega_1$ by $\omega_2 = (r_1/r_2)\omega_1$.
- $\tau$ is the input torque applied to the driving shaft.
- $J_1, J_2$ are moments of inertia, $b_1, b_2$ are damping coefficients, and $r_1, r_2$ are the radii of the pulleys.

Perform a system analysis to determine the dynamics from the input torque to the machine's velocity and position.

## Subproblems
1. Calculate the transfer function $G(s) = \frac{\Omega_2(s)}{T(s)}$ from the input torque $\tau$ to the machine's angular velocity $\omega_2$.
2. Calculate the transfer function $H(s) = \frac{\Theta_2(s)}{T(s)}$ from the input torque $\tau$ to the machine's angular position $\theta_2(t) = \int_{0}^{t} \omega_2(\tau) d\tau$.
3. Determine if the transfer functions $G(s)$ and $H(s)$ are asymptotically stable, assuming all physical constants ($J, b, r$) are positive.

## Additional Information
- The Laplace transform of the angular position is $\Theta_2(s) = \frac{\Omega_2(s)}{s}$ assuming zero initial conditions.
- A system is asymptotically stable if and only if all poles of its transfer function lie strictly in the open left-half of the complex $s$-plane ($\text{Re}(s) < 0$).

## Constraints
- Assume zero initial conditions for all variables.
- All derivations must be shown explicitly.
- The final transfer functions should be expressed in terms of the simplified parameters $\alpha$ and $\beta$.