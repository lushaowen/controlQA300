# Problem

## Problem Description

You have shown that the ordinary differential equation

\[
R C_{2} \dot{v}_{0} + R C_{1} \dot{v} + v = 0
\]

is an approximate model for the electric circuit in Fig. 2.23. Calculate the transfer-function from the input voltage, \( v \), to the output voltage, \( v_{0} \). Assume that all constants are positive. Is this transfer-function asymptotically stable?

## Subproblems

1. Rewrite the given differential equation in a form suitable for applying the Laplace transform.
2. Apply the Laplace transform under zero initial conditions.
3. Express the relationship between \( V_0(s) \) and \( V(s) \).
4. Derive the transfer-function \( G(s) = \frac{V_0(s)}{V(s)} \).
5. Identify the poles and zeros of the transfer-function.
6. Analyze whether the system is asymptotically stable based on pole locations.

## Additional Information

- The circuit is assumed to be linear and time-invariant.
- Initial conditions are assumed to be zero.
- Stability should be assessed using standard continuous-time LTI system theory.
- All circuit parameters \( R, C_1, C_2 \) are strictly positive.

## Constraints

- The derivation must use Laplace transform techniques.
- Stability analysis must be based on pole locations in the complex plane.
- The final transfer-function should be expressed in a simplified rational form.
- Mathematical steps should be clearly justified.
