# Problem

## Problem Description
Calculate the (open-loop) motor torque, \( \tau \) , for the rotating machine model in P2.10 and P2.12 so that the rotational speed of the mass \( {J}_{2},{\omega }_{2} \) , converges to \( {\overline{\omega }}_{2} = \) 4 rad/s as \( t \) gets large. Use the same data as in P2.13 and sketch or use MATLAB to plot the response, \( {\omega }_{2}\left( t\right) \) , when \( {\omega }_{2}\left( 0\right)  = 0\mathrm{{rad}}/\mathrm{s},{\omega }_{2}\left( 0\right)  = 3\mathrm{{rad}}/\mathrm{s} \) , or \( {\omega }_{2}\left( 0\right)  = 6\mathrm{{rad}}/\mathrm{s} \) .

## Subproblems
1. Determine the steady-state relationship between torque \( \tau \) and angular velocity \( \omega_1 \).
2. Relate the desired steady-state speed \( \overline{\omega}_2 \) to \( \overline{\omega}_1 \) using the belt constraint.
3. Compute the required open-loop motor torque \( \overline{\tau} \).
4. Write the corresponding time-domain response of \( \omega_2(t) \).
5. Sketch or simulate the response for different initial conditions of \( \omega_2 \).

---

## Additional Information
- The belt is inextensible and does not slip.
- Viscous friction torques act on both inertias.
- The system is linear and time-invariant.
- The input torque is constant (open-loop control).

Numerical values (same as P2.13):
\[
r_1 = 25~\mathrm{mm}, \quad r_2 = 500~\mathrm{mm},
\]
\[
b_1 = 0.01~\mathrm{kg\,m^2/s}, \quad b_2 = 0.1~\mathrm{kg\,m^2/s},
\]
\[
J_1 = 0.0031~\mathrm{kg\,m^2}, \quad J_2 = 25~\mathrm{kg\,m^2}.
\]

---

## Constraints
- The torque must be computed using steady-state analysis.
- The result must be consistent with the dynamic model from P2.12.
- Initial conditions must not affect the steady-state value.
- The final model must remain open-loop (no feedback).
