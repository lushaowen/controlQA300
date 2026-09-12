# Problem

## Problem Description
In [Ste+03], the authors have determined experimentally that the values

\[
{T}_{\mathrm{i}} = 100, \quad
{T}_{\mathrm{d}} = 38, \quad
{K}_{\mathrm{p}} = 0.17
\]

for the “controller” proposed in (6.26) in P6.38 seem to match the physiological response of glucose level to insulin plasma delivery.

1. Calculate the transfer-function corresponding to the controller (6.26).
2. Use the values of \( {T}_{\mathrm{i}} \) and \( {T}_{\mathrm{d}} \) above and calculate the loop transfer-function \( L(s) \) that can be used for feedback analysis of the closed-loop glucose homeostasis system with respect to the proportional gain \( {K}_{\mathrm{p}} > 0 \).
3. Sketch the corresponding root-locus diagram.
4. Determine whether the closed-loop insulin homeostasis system is asymptotically stable.

## Subproblems
1. Take the Laplace transform of the PID control law (6.26).
2. Express the controller in standard transfer-function form.
3. Identify the poles and zeros introduced by the controller.
4. Construct the loop transfer-function using the linearized glucose–insulin plant.
5. Analyze the pole–zero configuration of the open-loop system.
6. Predict qualitative root-locus behavior as \( K_p \) varies.
7. Determine whether all closed-loop poles can be placed in the left half-plane.

## Additional Information
- The plant has a negative static gain.
- Integral action introduces a pole at the origin.
- Derivative action introduces a zero.
- Parameters are obtained from experimental physiological data.
- Stability must be assessed using classical control tools.

## Constraints
- The controller structure must be exactly that of (6.26).
- Root-locus analysis must treat \( K_p \) as the variable gain.
- No numerical simulation is required.
- The analysis must be consistent with linearized system assumptions.
