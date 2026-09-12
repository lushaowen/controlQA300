# Problem

## Problem Description
You have shown that the ordinary differential equation

\[
J\dot{\omega } + \left( {b + \frac{{K}_{\mathrm{t}}{K}_{\mathrm{e}}}{{R}_{\mathrm{a}}}}\right) \omega  = \frac{{K}_{\mathrm{t}}}{{R}_{\mathrm{a}}}{v}_{\mathrm{a}}
\]

is a simplified description of the motion of the rotor of the DC motor in Fig. 2.24, where \( \omega \) is the rotor angular velocity.

Let the armature voltage, \( {v}_{\mathrm{a}} \), be the input and let the angular velocity, \( \omega \), be the output, and represent this equation in a block-diagram using only integrators. Rewrite the differential equation in state-space form.

![](images\image.png)
Fig2.24
## Subproblems
1. Identify the input and output variables of the DC motor model.
2. Isolate the highest derivative in the given differential equation.
3. Choose an appropriate state variable for the system.
4. Rewrite the equation in standard first-order state-space form.
5. Construct an integrator-based block-diagram representation.
6. Interpret the physical meaning of each term in the state equation.

## Additional Information
- The model represents a simplified DC motor with electrical dynamics neglected.
- All parameters \( J, b, K_t, K_e, R_a \) are positive constants.
- The system is assumed to be linear and time-invariant.
- Back electromotive force is included via the \( K_t K_e / R_a \) term.

## Constraints
- Only integrators may be used for dynamic elements.
- The state-space model must be first-order.
- The input must be the armature voltage \( v_a \).
- The output must be the angular velocity \( \omega \).
