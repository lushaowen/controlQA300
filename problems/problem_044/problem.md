# Problem: DC Motor Dynamics with Non-Negligible Armature Inductance

## Problem Description

In many DC motor models, the armature inductance \( L_a \) is neglected to simplify the dynamics.
However, when \( L_a > 0 \) is not negligible, the electrical and mechanical subsystems become more tightly coupled.

Redo the DC motor derivation using the full electrical and mechanical equations to show that the motor speed \( \omega(t) \) satisfies the second-order differential equation:

\[
J L_a \ddot{\omega}
+\left(J R_a + b L_a\right)\dot{\omega}
+\left(K_e K_t + b R_a\right)\omega
= K_t v_a
\]

Then show that this equation reduces to the standard first-order motor equation when the armature inductance is neglected, i.e., when \( L_a = 0 \).

---

## Subproblems

1. Write the electrical equation of the DC motor using Kirchhoff’s voltage law.
2. Write the mechanical equation of motion for the motor.
3. Eliminate the armature current \( i_a \) to obtain a differential equation in \( \omega \).
4. Derive the full second-order differential equation when \( L_a > 0 \).
5. Simplify the equation by setting \( L_a = 0 \).
6. Interpret the physical meaning of neglecting armature inductance.

---

## Additional Information

- Electrical equation:
  \[
  v_a = R_a i_a + L_a \dot{i}_a + K_e \omega
  \]
- Mechanical equation:
  \[
  J \dot{\omega} + b \omega = K_t i_a
  \]
- \( J \): rotor inertia  
- \( b \): viscous friction coefficient  
- \( K_t \), \( K_e \): motor constants  
- \( R_a \), \( L_a \): armature resistance and inductance  

---

## Constraints

- Assume linear motor behavior.
- Ignore nonlinear friction and magnetic saturation.
- All algebraic steps must be shown.
- Use SI units throughout.
