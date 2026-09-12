# Problem

## Problem Description
You were shown in Section that the nonlinear differential equation

\[
{J}_{\mathrm{r}}\ddot{\theta} + b\dot{\theta} + {mgr}\sin \theta  = u
\]

is an approximate model for the motion of the simple pendulum in Fig. 5.11 and that \( \left( {\overline{\theta },\bar{u}}\right)  = \left( {0,0}\right) \) and \( \left( {\overline{\theta },\bar{u}}\right)  = \left( {\pi ,0}\right) \) are the pendulum equilibrium points. Calculate the nonlinear differential equation obtained in closed-loop with the linear proportional controller

\[
u = {K}_{\mathrm{p}}e - {K}_{\mathrm{d}}\dot{e},\;e = \overline{\theta } - \theta .
\]

Show that \( \left( {\overline{\theta },\bar{u}}\right)  = \left( {0,0}\right) \) and \( \left( {\overline{\theta },\bar{u}}\right)  = \left( {\pi ,0}\right) \) are still equilibrium points. Linearize the closed-loop system linearized about \( \left( {\overline{\theta },\bar{u}}\right)  = \left( {0,0}\right) \) and \( \left( {\overline{\theta },\bar{u}}\right)  = \left( {\pi ,0}\right) \) and calculate the associated transfer-function. Assuming all constants are positive, find the range of values of \( K_p \) and \( K_d \) that stabilize both equilibrium points.

## Subproblems
1. Derive the closed-loop nonlinear differential equation by substituting the PD control law `u = K_p e - K_d \dot{e}` into the pendulum dynamics.
2. Verify that `(θ̅, ū) = (0, 0)` and `(θ̅, ū) = (π, 0)` satisfy the equilibrium conditions for the closed-loop system.
3. Construct a state-space representation suitable for linearization (e.g., using states `x₁ = θ` and `x₂ = \dot{θ}`).
4. Linearize the closed-loop system about the equilibrium point `(θ̅, ū) = (0, 0)` and derive the associated transfer function `Θ(s)/R(s)`.
5. Linearize the closed-loop system about the equilibrium point `(θ̅, ū) = (π, 0)` and derive the associated transfer function `Θ(s)/R(s)`.
6. Analyze the stability of each linearized system using the characteristic equation or eigenvalue analysis.
7. Determine the necessary and sufficient conditions on the controller gains `K_p` and `K_d` (given positive physical constants) such that both equilibrium points are stabilized.

## Additional Information
- The system is a simple pendulum with moment of inertia `J_r`, viscous damping coefficient `b`, mass `m`, gravitational acceleration `g`, and pendulum length `r`.
- The controller is a linear Proportional-Derivative (PD) controller acting on the tracking error `e = θ̅ - θ`, where `θ̅ = r` is the reference signal.
- Linearization is performed using the Jacobian method (first-order Taylor expansion) about the specified equilibrium points.
- Stability analysis for the linearized systems is based on the locations of the eigenvalues of the system matrix (or the roots of the characteristic polynomial).

## Constraints
- All physical constants (`J_r`, `b`, `m`, `g`, `r`) are positive.
- The final stability condition must be expressed as explicit inequalities for `K_p` and `K_d`.
- State-space representation and linearization steps must be clearly shown.