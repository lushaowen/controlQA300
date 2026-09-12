# Problem

## Problem Description
Determine a first-order ordinary differential equation based on P2.10 and P2.12 to describe the rotating machine as a dynamic system where the output is the angular velocity of the inertia \( {J}_{2},{\omega }_{2} \) , and the input is the motor torque, \( \tau \) . Calculate the solution to this equation. Consider \( \tau  = 1\mathrm{\;N}\mathrm{\;m},{r}_{1} = {25}\mathrm{\;{mm}},{r}_{2} = {500}\mathrm{\;{mm}},{b}_{1} = {0.01}\mathrm{\;{kg}}{\mathrm{\;m}}^{2}/\mathrm{s} \) , \( {b}_{2} = {0.1}\mathrm{\;{kg}}{\mathrm{\;m}}^{2}/\mathrm{s},{J}_{1} = {0.0031}\mathrm{\;{kg}}{\mathrm{\;m}}^{2},{J}_{2} = {25}\mathrm{\;{kg}}{\mathrm{\;m}}^{2} \) . Sketch or use MATLAB to plot the response, \( {\omega }_{2}\left( t\right) \) , when \( {\omega }_{2}\left( 0\right)  = 0\mathrm{{rad}}/\mathrm{s},{\omega }_{2}\left( 0\right)  = 3\mathrm{{rad}}/\mathrm{s} \) , or \( {\omega }_{2}\left( 0\right)  = 6\mathrm{{rad}}/\mathrm{s} \) .

## Subproblems
1. Write the reduced first-order differential equation obtained in P2.12.
2. Solve the differential equation for constant input torque \( \tau = \overline{\tau} \).
3. Express the output angular velocity \( \omega_2(t) \) in terms of \( \omega_1(t) \).
4. Translate initial conditions on \( \omega_2 \) into equivalent initial conditions on \( \omega_1 \).
5. Compute numerical values of the steady-state speed and time constant using the given parameters.
6. Sketch or simulate the response \( \omega_2(t) \) for different initial conditions.

---

## Additional Information
- The belt does not slip, so angular velocities are related by pulley radii.
- The system is linear and time-invariant.
- The input torque is constant.
- All physical parameters are known.

Given numerical values:
\[
\tau = 1~\mathrm{N\,m}, \quad
r_1 = 25~\mathrm{mm}, \quad
r_2 = 500~\mathrm{mm},
\]
\[
b_1 = 0.01~\mathrm{kg\,m^2/s}, \quad
b_2 = 0.1~\mathrm{kg\,m^2/s},
\]
\[
J_1 = 0.0031~\mathrm{kg\,m^2}, \quad
J_2 = 25~\mathrm{kg\,m^2}.
\]

---

## Constraints
- The final model must be a first-order ordinary differential equation.
- Clearly identify the system input and output.
- Show how the initial conditions are transformed.
- Numerical results must be physically interpretable.
