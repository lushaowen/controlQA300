# Problem

## Problem Description

You have shown  that the ordinary differential equation:

\[
m\ddot{x} + b\dot{x} + {kx} = f + {mg}\sin \theta
\]

is a simplified description of the motion of the mass-spring-damper system in Fig. 2.19(b), where \( g \) is the gravitational acceleration and \( {x}_{0} \) is equal to the spring rest length \( {\ell }_{0} \). The additional force, \( f \), will be used as a control input. Let \( g = {10}\mathrm{\;m}/{\mathrm{s}}^{2} \), \( m = 1\mathrm{\;kg} \), \( k = 1\mathrm{\;N}/\mathrm{m} \), and \( b = {0.1}\mathrm{\;kg}/\mathrm{s} \), and use the root-locus method to design a dynamic feedback controller that uses \( f \) as control input and \( x \) as the measured output and that can regulate the position, \( x \), at zero for any constant possible value of inclination \( \theta \in \left( {-\pi /2,\pi /2} \right) \).

Hint: Treat the inclination as a disturbance.
![](images\image.png)
Fig. 2.19

## Subproblems

1. Rewrite the equation of motion in normalized state-space or transfer-function form.
2. Identify the physical meaning of each parameter in the normalized model.
3. Determine the open-loop transfer function from the control input \( f \) to the output \( x \).
4. Explain why the inclination angle \( \theta \) can be treated as a constant disturbance.
5. Determine what controller structure is required to reject constant disturbances.
6. Use root-locus arguments to justify the choice of controller dynamics.
7. Discuss the closed-loop stability for small positive controller gain values.

## Additional Information

- The inclination angle \( \theta \) is constant but unknown.
- The controller must achieve zero steady-state error in position.
- Only position measurement \( x \) is available for feedback.
- Root-locus analysis should be used qualitatively to justify stability.

## Constraints

- The controller must be linear and time-invariant.
- Only dynamic output feedback is allowed.
- The design must ensure internal stability.
- Controller complexity should be kept minimal.
