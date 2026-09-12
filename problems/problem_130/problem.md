# Problem

## Problem Description

Consider the closed-loop connection in Fig. 4.20(b) with \( v = 0 \) and the system and controller transfer-functions

\[
G(s) = \frac{1}{s},\; K(s) = \frac{(s + 1)^2}{s^2 + 1}.
\]

Show that the closed-loop system asymptotically tracks a constant reference input
\( y(t) = \bar{y}, t \geq 0 \),
and asymptotically rejects an input disturbance
\( w(t) = \bar{w} \cos(t), t \geq 0 \).

## Subproblems

1. Compute the open-loop transfer function \( GK \).
2. Derive the sensitivity function \( S(s) \).
3. Derive the disturbance transfer function \( D(s) \).
4. Determine the poles of \( S(s) \) and assess internal stability.
5. Analyze the low-frequency behavior of \( S(s) \) to evaluate reference tracking.
6. Analyze the frequency response of \( D(s) \) at \( \omega = 1 \).
7. Conclude whether constant reference tracking and sinusoidal disturbance rejection are achieved.

## Additional Information

- The closed-loop structure corresponds to Fig. 4.20(b).
- The reference input enters at the summing junction.
- The disturbance is additive at the plant input.
- All systems are linear, time-invariant, and continuous-time.

## Constraints

- Use frequency-domain and transfer-function analysis.
- Stability must be verified before performance conclusions.
- Disturbance rejection must be justified via zeros of \( D(s) \).
- Do not rely on simulation-based arguments.
