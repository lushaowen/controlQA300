# Problem

## Problem Description

You have shown  that the ordinary differential equations

\[
{m}_{1}{\ddot{x}}_{1} + \left( {{b}_{1} + {b}_{2}}\right) {\dot{x}}_{1} + \left( {{k}_{1} + {k}_{2}}\right) {x}_{1} - {b}_{2}{\dot{x}}_{2} - {k}_{2}{x}_{2} = 0,
\]

\[
{m}_{2}{\ddot{x}}_{2} + {b}_{2}\left( {{\dot{x}}_{2} - {\dot{x}}_{1}}\right)  + {k}_{2}\left( {{x}_{2} - {x}_{1}}\right)  = {f}_{2}
\]

are a simplified description of the motion of the mass-spring-damper system in Fig. 2.20(b), where \( {x}_{1} \) and \( {x}_{2} \) are the positions of the masses \( {m}_{1} \) and \( {m}_{2} \) and \( {f}_{2} \) is a force applied on mass \( {m}_{2} \). Calculate the transfer-function from the force \( {f}_{2} \) to the position \( {x}_{1} \).
![alt text](images\image.png)
## Subproblems

1. Apply the Laplace transform to the coupled differential equations assuming zero initial conditions.
2. Express the equations in algebraic form using \( X_1(s) \), \( X_2(s) \), and \( F_2(s) \).
3. Solve the second equation for \( X_2(s) \) in terms of \( X_1(s) \) and \( F_2(s) \).
4. Substitute the expression for \( X_2(s) \) into the first equation.
5. Isolate the ratio \( \frac{X_1(s)}{F_2(s)} \) to obtain the transfer function.
6. Interpret the structure and order of the resulting transfer function.

## Additional Information

- The system consists of two coupled masses connected by springs and dampers.
- All parameters \( m_1, m_2, b_1, b_2, k_1, k_2 \) are assumed positive constants.
- Initial displacements and velocities are zero.
- The force input is applied only to the second mass.

## Constraints

- Laplace-domain analysis must be used.
- Algebraic manipulation steps should be logically consistent.
- The final transfer function must be expressed as a ratio of polynomials in \( s \).
- No numerical substitution is required.
