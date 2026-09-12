# Problem

## Problem Description

You have shown that the ordinary differential equation

\[
m\ddot{x} + b\dot{x} + kx = f + mg\sin \theta
\]

is a simplified description of the motion of the mass-spring-damper system in Fig. 2.19(b), where \( g \) is the gravitational acceleration and \( x_0 \) is equal to the spring rest length \( \ell_0 \). The additional force, \( f \), will be used as a control input. Let \( g = 10\,\mathrm{m/s^2} \), \( m = 1\,\mathrm{kg} \), \( k = 1\,\mathrm{N/m} \), and \( b = 0.1\,\mathrm{kg/s} \), and use Bode plots and the Nyquist stability criterion to design a dynamic feedback controller that uses \( f \) as control input and \( x \) as the measured output and that can regulate the position, \( x \), at zero for any constant possible value of inclination \( \theta \in (-\pi/2,\pi/2) \). Calculate the corresponding gain and phase margins. Hint: Treat the inclination as a disturbance.
![](images\image.png)
Fig2.19
## Subproblems

1. Rewrite the equation of motion in normalized form and identify all system parameters.
2. Derive the open-loop transfer function from control input \( f \) to output \( x \).
3. Interpret the inclination term \( mg\sin\theta \) as an external disturbance acting on the system.
4. Explain why disturbance rejection of constant inputs requires a controller with integral action.
5. Propose a suitable dynamic feedback controller structure and justify the choice.
6. Analyze the open-loop system using Bode plots and determine stability margins.
7. Apply the Nyquist stability criterion to determine the allowable controller gain range.
8. Compute the gain margin and phase margin for the selected controller parameters.

## Additional Information

- The system is assumed to be linear and time-invariant.
- Small-angle approximations are not applied; \( \sin\theta \) is treated as a bounded constant disturbance.
- The controller design focuses on asymptotic regulation rather than transient performance optimization.
- All stability conclusions should be supported by frequency-domain analysis.

## Constraints

- The controller must be dynamic and physically realizable.
- The closed-loop system must remain stable for all constant \( \theta \in (-\pi/2,\pi/2) \).
- Stability analysis must explicitly use Bode plots and the Nyquist criterion.
- Numerical values should be computed using the given physical parameters.
