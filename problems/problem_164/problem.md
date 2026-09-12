# Problem

## Problem Description

The ordinary differential equation

\[
m\dot{v} + bv|v| = mg
\]

is a simplified description of the motion of an object of mass \( m \) dropping vertically under constant gravitational acceleration \( g \), and quadratic air resistance \( -bv|v| \).

Let the gravitational force \( mg \) be the input and the vertical velocity \( v \) be the output.

Represent this equation in a block-diagram using only integrators. Rewrite the differential equation in state-space form.

## Subproblems

1. Isolate the highest-order derivative in the given differential equation.
2. Define appropriate state, input, and output variables.
3. Rewrite the system as a first-order nonlinear state-space model.
4. Identify the nonlinear term introduced by quadratic air resistance.
5. Construct a block-diagram representation using only integrator blocks.
6. Explain the physical meaning of each block and signal in the diagram.

## Additional Information

- The velocity \( v \) is taken as positive in the downward direction.
- Air resistance is proportional to the square of the velocity magnitude.
- The system is nonlinear due to the term \( v|v| \).
- The block-diagram should not include differentiators.

## Constraints

- Use only integrators in the block-diagram representation.
- The input must be explicitly defined as the gravitational force.
- The state-space form must be first-order.
- Clearly distinguish between linear and nonlinear components.
