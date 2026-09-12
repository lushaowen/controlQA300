# Problem

## Problem Description

You have shown that the ordinary differential equation

\[
m\dot{v} + {bv} = {mg}
\]

is a simplified description of the motion of an object of mass \( m \) dropping vertically under constant gravitational acceleration, \( g \) , and linear air resistance, \( - {bv} \) . Let the gravitational force, \( {mg} \) , be the input and let the vertical velocity, \( v \) , be the output, and represent this equation in a block-diagram using only integrators. Rewrite the differential equation in state-space form.

## Subproblems

1. Identify the system input, output, and state variables.
2. Rewrite the differential equation by isolating the highest derivative.
3. Express the system in standard state-space form.
4. Construct a block-diagram representation using only integrators.
5. Interpret the physical meaning of each term in the model.

## Additional Information

- The motion is assumed to be one-dimensional and vertical.
- Air resistance is modeled as a linear function of velocity.
- Gravitational acceleration is constant.
- The system is linear and time-invariant.
- Initial conditions are not specified.

## Constraints

- Only integrator blocks may be used in the block-diagram.
- The state-space model must be minimal.
- Use standard control-system notation.
- Physical interpretation should be consistent with the mathematical model.
- No nonlinear drag effects are considered.
