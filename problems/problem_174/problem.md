# Problem

## Problem Description
 the rotor torque is

\[
\tau = K_{\mathrm{t}} i_{\mathrm{a}}
\]

where the armature current, \( i_{\mathrm{a}} \), is related to the armature voltage, \( v_{\mathrm{a}} \), and the rotor angular velocity, \( \omega \), through

\[
v_{\mathrm{a}} = R_{\mathrm{a}} i_{\mathrm{a}} + K_{\mathrm{e}} \omega .
\]

, let the armature voltage, \( v_{\mathrm{a}} \), be the input and let the torque, \( \tau \), be the output, and represent this equation in a block-diagram using only integrators. Rewrite the differential equation in state-space form and calculate the associated transfer-function.

## Subproblems
1. Express the armature current \( i_a \) in terms of \( v_a \) and \( \omega \).
2. Substitute the current expression into the torque equation.
3. Combine the electrical and mechanical equations into a state-space model.
4. Identify the state, input, and output variables.
5. Compute the transfer function from \( v_a \) to \( \tau \).
6. Compare the resulting transfer function with that obtained in P4.34.

## Additional Information
- The DC motor model neglects armature inductance.
- All parameters \( J, b, K_t, K_e, R_a \) are positive constants.
- The system is linear and time-invariant.
- The block-diagram must consist only of integrators and static gains.

## Constraints
- Only integrator blocks may represent dynamics.
- The state-space model must be first-order.
- The input is the armature voltage \( v_a \).
- The output is the electromagnetic torque \( \tau \).
