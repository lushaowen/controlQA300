# Problem

## Problem Description

You were shown in Section 5.5 that the nonlinear differential equation

\[
{J}_{\mathrm{r}}\ddot{y} + b\dot{y} + {mgr}\sin \theta  = u
\]

is an approximate model for the motion of the simple pendulum in Fig. 5.11 and that \( \left( {\overline{\theta },\bar{u}}\right)  = \left( {0,0}\right) \) and \( \left( {\overline{\theta },\bar{u}}\right)  = \left( {\pi ,0}\right) \) are the pendulum equilibrium points. Calculate the nonlinear differential equation obtained in closed-loop with the linear proportional controller

\[
u = {Ke},\;e = \overline{\theta } - \theta .
\]

Show that \( \left( {\overline{\theta },\bar{u}}\right)  = \left( {0,0}\right) \) and \( \left( {\overline{\theta },\bar{u}}\right)  = \left( {\pi ,0}\right) \) are still equilibrium points. Linearize the closed-loop system linearized about \( \left( {\overline{\theta },\bar{u}}\right)  = \left( {0,0}\right) \) and \( \left( {\overline{\theta },\bar{u}}\right)  = \left( {\pi ,0}\right) \) and calculate the associated transfer-function. Assuming all constants are positive, find the range of values of \( K \) that stabilize both equilibrium points.

## Subproblems

1. Write the closed-loop nonlinear differential equation using the proportional control law.
2. Express the closed-loop dynamics in state-space form.
3. Determine the equilibrium points of the closed-loop nonlinear system.
4. Linearize the closed-loop system about the downward equilibrium point.
5. Linearize the closed-loop system about the upright equilibrium point.
6. Compute the eigenvalues of each linearized system.
7. Determine the conditions on the gain \( K \) for local asymptotic stability at each equilibrium.
8. Identify the range of \( K \) that stabilizes both equilibria simultaneously.

## Additional Information

- The pendulum model is nonlinear due to the sine term.
- Linearization is performed using small-signal approximations.
- Stability is assessed via eigenvalue locations of the linearized system.
- All physical parameters are assumed strictly positive.

## Constraints

- No small-angle approximation is allowed prior to linearization.
- The controller is restricted to proportional feedback.
- Stability must be determined using linearized models.
- The final result should provide an explicit inequality on \( K \).
