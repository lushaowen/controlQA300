# Problem

## Problem Description
Modify the feedback controller so that the closed-loop elevator system can asymptotically track a constant reference

\[
{\bar{x}}_{1}\left( t\right) = {\bar{x}}_{1} = 10\,\mathrm{m}, \quad t \geq 0,
\]

when

\[
{m}_{2} = 800\,\mathrm{kg}.
\]

## Subproblems
1. Recall the plant transfer function from torque input \( \tau \) to position output \( x_1 \).
2. Explain why asymptotic tracking of constant references requires integral action.
3. Discuss why a pure integral controller cannot stabilize the closed-loop system.
4. Propose a controller structure that includes both an integrator and a zero.
5. Derive the closed-loop sensitivity function for the modified controller.
6. Determine conditions on the controller parameters that ensure internal stability.
7. Explain how the modified controller achieves both tracking and disturbance rejection.

## Additional Information
- The parameters \( \alpha \) and \( \beta \) are as defined in P4.25.
- The mass imbalance \( m_1 \neq m_2 \) introduces a constant input disturbance.
- The system is linear and time-invariant.
- Controller design is restricted to classical transfer-function methods.

## Constraints
- Use Laplace-domain analysis.
- Stability must be justified using closed-loop pole locations.
- The controller must include integral action.
- Only single-input single-output (SISO) feedback is allowed.
