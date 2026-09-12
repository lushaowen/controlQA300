# Problem

## Problem Description

with a controller

\[
{v}_{\mathrm{a}} = {K}_{\mathrm{i}}\left( {\overline{\theta } - \theta }\right) ,
\]

where

\[
\theta \left( t\right)  = \theta \left( 0\right)  + {\int }_{0}^{t}\omega \left( \tau \right) {d\tau },
\]

and the angular reference  
\( \overline{\theta }\left( t\right)  = \overline{\theta } = \pi , t \geq  0 \) .

## Subproblems

1. Express the relationship between angular velocity and angular position in the Laplace domain.
2. Derive the transfer function from armature voltage to angular position.
3. Write the proportional controller acting on angular position error.
4. Formulate the open-loop transfer function of the combined plant and controller.
5. Determine the type of the resulting closed-loop system.
6. Analyze internal stability of the closed-loop system.
7. Determine whether the system can asymptotically track a constant angular reference.
8. Compare this control structure with velocity-feedback integral control.
9. Describe the qualitative characteristics of the closed-loop time response.

## Additional Information

- The DC motor velocity dynamics are assumed to be first order.
- Angular position is obtained by integrating angular velocity.
- The controller is proportional with respect to position error.
- Zero initial conditions are assumed unless otherwise specified.
- Reference input is a constant angular displacement.

## Constraints

- All analysis should be carried out using linear control theory.
- Stability conclusions must be based on pole locations.
- Tracking properties should be justified analytically.
- Units of angular quantities must r
