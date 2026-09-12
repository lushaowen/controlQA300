# Problem

## Problem Description
you reproduced the results of [Ste+03] by verifying using the root-locus method that the PID controller (6.26) is capable of stabilizing the insulin homeostasis system in closed-loop.

Use the values \( {T}_{\mathrm{i}} = {100} \) and \( {T}_{\mathrm{d}} = {38} \) , and calculate the loop transfer-function, \( L\left( s\right) \) , that can be used for feedback analysis of the closed-loop glucose homeostasis system with respect to the proportional gain, \( {K}_{\mathrm{p}} > 0 \) , and sketch the corresponding Bode and polar plots.

Use the Nyquist stability criterion to show that the closed-loop insulin homeostasis system is asymptotically stable.

## Subproblems
1. Recall the linearized transfer function of the glucose–insulin dynamics.
2. Write down the PID controller transfer function using the given \( T_i \) and \( T_d \).
3. Derive the loop transfer function \( L(s) \) with respect to \( K_p \).
4. Identify all poles and zeros of the open-loop system.
5. Sketch or compute the Bode magnitude and phase plots of \( L(s) \).
6. Sketch the Nyquist (polar) plot of \( L(s) \).
7. Apply the Nyquist stability criterion to assess closed-loop stability.
8. Interpret the stability result for all \( K_p > 0 \).

## Additional Information
- The glucose–insulin model is linearized around a physiological equilibrium.
- The PID controller is implemented in positive feedback.
- Parameter values are taken from [Ste+03].
- Stability is assessed using frequency-domain methods rather than time-domain simulation.

## Constraints
- Only proportional gain \( K_p \) is varied.
- Integral and derivative time constants are fixed.
- Linear control assumptions apply.
- Stability must be justified using Nyquist arguments.
