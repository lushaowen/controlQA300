# Problem: DC Motor Parameter Estimation Using Added Inertia and Time Constant

## Problem Description

DC motors equipped with high-ratio gearboxes can be damaged if held in place, making stall-torque experiments impractical.
An alternative approach is to estimate motor parameters by observing changes in the motor time constant after adding external inertia.

A DC motor has an armature resistance
\[
R_a = 0.2\;\Omega.
\]

After attaching an additional rotational inertia
\[
J' = 0.001\;\mathrm{kg\,m^2},
\]
the measured motor time constant becomes
\[
\tau_m' = 0.54\;\mathrm{s}.
\]

Using this information, estimate the following motor parameters:

- Rotor inertia \( J \)
- Torque constant \( K_t \)
- Back-emf constant \( K_e \)
- Viscous friction coefficient \( b \)

---

## Subproblems

1. Explain how the motor time constant depends on inertia and damping.
2. Derive the relationship between the original and modified time constants.
3. Estimate the rotor inertia \( J \) using the added inertia method.
4. Compute the torque constant \( K_t \).
5. Determine the back-emf constant \( K_e \).
6. Calculate the viscous friction coefficient \( b \).
7. Discuss why this method avoids the risks associated with stall testing.

---

## Additional Information

- The mechanical pole of a DC motor is defined as:
  \[
  \alpha = \frac{1}{J}\left(b + \frac{K_t K_e}{R_a}\right)
  \]
- With added inertia:
  \[
  \alpha' = \frac{1}{J + J'}\left(b + \frac{K_t K_e}{R_a}\right)
  \]
- The original motor time constant is known to be:
  \[
  \tau_m = 0.1\;\mathrm{s}
  \]
- The nominal operating point is:
  - Armature voltage \( \bar{v}_a = 12\;\mathrm{V} \)
  - Speed \( \tilde{\omega} = 5000\;\mathrm{rpm} \)

---

## Constraints

- Assume linear DC motor behavior.
- Neglect nonlinear friction and magnetic saturation.
- All derivations must be shown.
- Use SI units throughout.
