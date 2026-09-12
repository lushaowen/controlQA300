# Problem

## Problem Description

You have shown that the ordinary differential equations

\[
m_{1}\ddot{x}_{1} + (b_{1} + b_{2})\dot{x}_{1} + (k_{1} + k_{2})x_{1} - b_{2}\dot{x}_{2} - k_{2}x_{2} = f_{1},
\]

\[
m_{2}\ddot{x}_{2} + b_{2}(\dot{x}_{2} - \dot{x}_{1}) + k_{2}(x_{2} - x_{1}) = f_{2}
\]

constitute a simplified description of the motion of the mass-spring-damper system in Fig. 2.20(b), where \( x_{1} \) and \( x_{2} \) are displacements, and \( f_{1} \) and \( f_{2} \) are forces applied on the masses \( m_{1} \) and \( m_{2} \). Let the force, \( f_{2} \), be the control input and let the displacement, \( x_{2} \), be the measured output. Let \( m_{1} = m_{2} = 1\,\mathrm{kg}, b_{1} = b_{2} = 0.1\,\mathrm{kg/s}, k_{1} = 1\,\mathrm{N/m} \), and \( k_{2} = 2\,\mathrm{N/m} \). Use Bode plots and the Nyquist stability criterion to design a dynamic feedback controller that uses \( f_{2} \) as control input and \( x_{2} \) as the measured output and that can regulate the position, \( x_{2} \), at zero for any constant possible value of force \( f_{1} \). Calculate the corresponding gain and phase margins. Hint: Treat the force \( f_{1} \) as a disturbance.

![](images\image.png)
Fig.2.20
## Subproblems

1. Derive the transfer functions from \( f_{1} \) and \( f_{2} \) to the output displacement \( x_{2} \).
2. Identify the pole-zero structure of the open-loop system and comment on its stability.
3. Interpret the force \( f_{1} \) as an external disturbance and analyze its effect on the output.
4. Explain why rejection of a constant disturbance requires integral action in the controller.
5. Propose a suitable dynamic controller structure that includes a pole at the origin.
6. Analyze the loop transfer function using Bode plots.
7. Apply the Nyquist stability criterion to determine closed-loop stability.
8. Compute and interpret the gain margin and phase margin for the selected controller.

## Additional Information

- The system is linear, time-invariant, and modeled using lumped parameters.
- All forces and displacements are assumed to be scalar and collinear.
- The disturbance force \( f_{1} \) is assumed to be constant but unknown.
- Frequency-domain tools are to be used for both controller design and stability assessment.

## Constraints

- The controller must be dynamic and realizable.
- The closed-loop system must be asymptotically stable.
- The output \( x_{2} \) must converge to zero for any constant \( f_{1} \).
- Stability analysis must explicitly use Bode plots and the Nyquist criterion.
