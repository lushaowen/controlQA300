# Problem

## Problem Description
 that the ordinary differential equation

\[
\left( {{J}_{1}{r}_{2}^{2} + {J}_{2}{r}_{1}^{2}}\right) {\dot{\omega }}_{1} + \left( {{b}_{1}{r}_{2}^{2} + {b}_{2}{r}_{1}^{2}}\right) {\omega }_{1} = {r}_{2}^{2}\tau ,\;{\omega }_{2} = \left( {{r}_{1}/{r}_{2}}\right) {\omega }_{1}
\]

is a simplified description of the motion of a rotating machine driven by a belt without slip as in Fig. 2.18(a), where $ {\omega }_{1} $ is the angular velocity of the driving shaft and $ {\omega }_{2} $ is the machine’s angular velocity. Let $ {r}_{1} = {25}\mathrm{\;{mm}},{r}_{2} = {500}\mathrm{\;{mm}},{b}_{1} = {0.01}\mathrm{\;{kg}}{\mathrm{\;m}}^{2}/\mathrm{s},{b}_{2} = \; {0.1}\mathrm{\;{kg}}{\mathrm{\;m}}^{2}/\mathrm{s},{J}_{1} = {0.0031}\mathrm{\;{kg}}{\mathrm{\;m}}^{2},{J}_{2} = {25}\mathrm{\;{kg}}{\mathrm{\;m}}^{2} $. Use the root-locus method to design an I controller:

\[
\tau \left( t\right)  = {K}_{\mathrm{i}}{\int }_{0}^{t}e\left( \sigma \right) {d\sigma },\;e = {\overline{\omega }}_{2} - {\omega }_{2},
\]

and select $ {K}_{\mathrm{i}} $ so that both closed-loop poles are real and as negative as possible. Is the closed-loop capable of asymptotically tracking a constant reference input $ {\overline{\omega }}_{2} $? Is the closed-loop capable of asymptotically rejecting a constant input torque disturbance?
![](images\image.png)
Fig.2.18
## Subproblems
1. Derive the transfer function from control input $\tau$ to output $\omega_2$, expressing it in terms of system parameters.
2. Determine the loop transfer function for the I-controlled system and identify its poles and zeros.
3. Construct the root-locus plot qualitatively and determine the value of $K_i$ that results in repeated real poles at the leftmost possible location.
4. Analyze whether the closed-loop system achieves asymptotic tracking of a constant reference signal.
5. Evaluate the system's ability to reject constant torque disturbances applied at the input.

## Additional Information 
- The mechanical system consists of two inertias connected via a belt drive with no slip, implying kinematic constraints between angular velocities.
- Damping terms $b_1$ and $b_2$ represent rotational friction on the motor and load sides, respectively.
- An integrator in the controller introduces a pole at the origin, which affects both stability margins and steady-state performance.
- Root locus analysis assumes variation of $K_i > 0$, and all physical parameters are positive constants.

## Constraints
- All derivations must be based on linear time-invariant (LTI) system assumptions.
- Only consider small-signal deviations around equilibrium for dynamic modeling.
- Justify pole placement choices using root-locus properties such as breakaway points and asymptotes.
- Final answers must include numerical evaluation of $K_i$ using given parameter values.
- Steady-state behavior analysis should invoke final value theorem or internal model principle.
