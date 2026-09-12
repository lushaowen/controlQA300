# Problem: Modeling of a Series RLC Circuit

## Problem Description

Consider the electric circuit shown in Fig. 2.22(b), where a resistor, an inductor, and a capacitor are connected in series. Let the applied voltage source be \( v(t) \).

According to Kirchhoff’s voltage law, the sum of the voltages around the loop must satisfy:
\[
-v + v_R + v_L + v_C = 0.
\]

The constitutive relations of the circuit elements are:
\[
i_C = C\dot{v}_C, \qquad v_R = Ri_R, \qquad v_L = L\dot{i}_L,
\]
where \( R \) is the resistance, \( C \) the capacitance, and \( L \) the inductance.

Because the elements are in series, the current through all components is the same:
\[
i_R = i_C = i_L = i.
\]

---

## Tasks

1. Use Kirchhoff’s voltage and current laws to derive a differential equation governing the circuit.
2. Express the equation solely in terms of the capacitor voltage \( v_C(t) \).
3. Identify the order of the resulting differential equation.
4. Compare this equation with the RC circuit equation from Problem 2.34.

---

## Additional Information

- All circuit elements are ideal and linear.
- The capacitor voltage \( v_C(t) \) is chosen as the system output.
- No initial conditions are required for this derivation.

---

## Constraints

- Use only Kirchhoff’s laws and element constitutive equations.
- Clearly justify each substitution.
- Final result must be a single ordinary differential equation.
