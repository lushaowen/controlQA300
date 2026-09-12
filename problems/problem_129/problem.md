# Problem

## Problem Description

Consider the closed-loop connection in Fig. 4.20(b) with \( v = 0 \) in which the system and controller transfer-functions are

\[
G(s) = \frac{1}{s},\; K(s) = 1.
\]

Does the closed-loop system achieve asymptotic rejection of a constant disturbance \( w(t) = \bar{w}, t \geq 0 \)?
![alt text](images/bo_d5cu3iv7aajc7381m5hg_1_321_282_1027_235_0.jpg)
## Subproblems

1. Write the open-loop transfer function \( GK \) and identify its poles.
2. Derive the sensitivity function \( S(s) \).
3. Derive the disturbance-to-output transfer function \( D(s) \).
4. Analyze the stability of \( S(s) \) and determine internal stability of the closed-loop system.
5. Examine the low-frequency (DC) behavior of \( D(s) \).
6. Determine whether a constant disturbance is asymptotically rejected and explain why.

## Additional Information

- The feedback structure corresponds to Fig. 4.20(b) with disturbance input \( w \).
- The disturbance enters additively at the plant input.
- All systems are linear, time-invariant, and continuous-time.
- Stability is assessed in the asymptotic sense.

## Constraints

- Use transfer-function and frequency-domain analysis.
- Do not assume disturbance rejection without checking DC gain.
- Clearly distinguish between internal stability and disturbance rejection.
- All reasoning must be analytical.
