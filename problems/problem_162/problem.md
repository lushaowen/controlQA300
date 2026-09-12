# Problem

## Problem Description

 considering the vertical position, \( x\left( t\right)  = x\left( 0\right)  + {\int }_{0}^{t}v\left( \tau \right) {d\tau } \) , as the output.

## Subproblems

1. Express the relationship between vertical position and velocity.
2. Augment the original state-space model from P5.8 to include position.
3. Identify the new state vector, system matrix, and input matrix.
4. Define the output equation corresponding to the vertical position.
5. Construct a block-diagram representation using integrators.
6. Compare the system order with that of the original P5.8 model.

## Additional Information

- The system models vertical motion under gravity with linear air resistance.
- The gravitational force is treated as the system input.
- The original P5.8 model used velocity as the output.
- Position is obtained by integrating velocity over time.
- Initial conditions are assumed known but unspecified.

## Constraints

- The model must be linear and time-invariant.
- Use standard state-space notation.
- Only integrators may be used in the block-diagram.
- Physical interpretation must remain consistent with the model.
- No nonlinear aerodynamic effects are considered.
