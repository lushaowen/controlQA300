# Problem

## Problem Description

The rotating machine in is connected to a piston that applies a periodic torque that can be approximated by
\( {\tau }_{2}\left( t\right)  = h\cos \left( {\sigma t}\right) \) ,
where the angular frequency \( \sigma \) is equal to the angular velocity \( {\omega }_{2} \) .
The modified equation including this additional torque is given by

\[
\left( {{J}_{1}{r}_{2}^{2} + {J}_{2}{r}_{1}^{2}}\right) {\dot{\omega }}_{1}
+\left( {{b}_{1}{r}_{2}^{2} + {b}_{2}{r}_{1}^{2}}\right) {\omega }_{1}
= {r}_{2}\left( {{r}_{2}\tau  + {r}_{1}{\tau }_{2}}\right),
\;{\omega }_{2} = \left( {{r}_{1}/{r}_{2}}\right) {\omega }_{1}.
\]

Use Bode plots and the Nyquist stability criterion to design a dynamic feedback controller that uses \( \tau \) as control input and \( {\omega }_{2} \) as the measured output so that the closed-loop system is capable of asymptotically tracking a constant reference input
\( {\overline{\omega }}_{2}\left( t\right)  = {\overline{\omega }}_{2} = 4\pi , \; t \ge 0 \),
and asymptotically rejecting the torque perturbation
\( {\tau }_{2}\left( t\right)  = h\cos \left( {\sigma t}\right) \)
when \( \sigma = {\overline{\omega }}_{2} \).
Calculate the corresponding gain and phase margins.

## Subproblems

1. Derive the transfer function from control torque \( \tau \) to output angular velocity \( \omega_2 \).
2. Identify the steady-state tracking and disturbance rejection requirements in the frequency domain.
3. Determine the necessary pole structure of the controller to achieve zero steady-state error for constant references.
4. Determine the controller structure required to reject a sinusoidal disturbance at \( \sigma = 4\pi \).
5. Propose a dynamic controller satisfying the internal model principle.
6. Analyze the open-loop transfer function using Bode plots.
7. Use the Nyquist stability criterion to verify closed-loop stability.
8. Determine admissible gain values ensuring asymptotic stability.
9. Calculate the corresponding gain and phase margins.

## Additional Information

- The plant is linear and time-invariant.
- The disturbance torque is periodic and acts additively on the plant.
- Only frequency-domain methods (Bode and Nyquist) are to be used.
- The reference signal is constant and applied at \( t = 0 \).
- All stability claims refer to asymptotic stability.

## Constraints

- The controller must be dynamic.
- Minimum phase behavior is assumed for the plant.
- The controller must include internal models for reference tracking and disturbance rejection.
- Closed-loop stability must be justified using the Nyquist criterion.
- Gain and phase margins must be clearly identified from frequency-response plots.
