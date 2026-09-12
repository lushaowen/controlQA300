# Problem

## Problem Description

Consider the closed-loop connection in Fig. 4.20(b) with \( w = 0 \) and the system and controller transfer-functions

\[
G(s) = \frac{1}{s + 1},\; K(s) = \frac{1}{s}.
\]

Calculate the steady-state component of the output, \( y \), and the tracking error,
\( e = \bar{y} - y \),
in response to

\[
\bar{y}(t) = \bar{y},\; v(t) = \bar{v} + \cos(\omega t),\; t \ge 0.
\]

Does the closed-loop achieve asymptotic tracking of the reference input,
\( \bar{y}(t) \)?
Does the closed-loop achieve asymptotic rejection of the measurement noise input,
\( v(t) \)?
What happens if \( \omega \) is very large and \( \bar{v} \) is zero?
![alt text](images/bo_d5cu3iv7aajc7381m5hg_1_321_282_1027_235_0.jpg)
Fig4.20
## Subproblems

1. Compute the open-loop transfer function \( GK \).
2. Derive the sensitivity function \( S(s) \).
3. Derive the transfer function \( H(s) \) from reference and noise to output.
4. Verify internal stability of the closed-loop system.
5. Compute the steady-state response to constant and sinusoidal inputs.
6. Determine the tracking error for constant reference input.
7. Analyze the effect of high-frequency measurement noise.

## Additional Information

- The configuration corresponds to Fig. 4.20(b).
- Measurement noise enters additively at the sensor.
- Steady-state analysis should be conducted in the frequency domain.
- The system is linear, time-invariant, and continuous-time.

## Constraints

- Assume zero initial conditions.
- Stability must be established before steady-state conclusions.
- Use transfer-function evaluation at \( s = j\omega \).
- Do not assume noise rejection without explicit frequency analysis.
