# Solution

## Method

We have

\[
G\left( s\right)  = \frac{\beta }{s + \alpha },\;\alpha  = \frac{b}{J} + \frac{{K}_{e}{K}_{t}}{J{R}_{a}},\;\beta  = \frac{{K}_{t}}{J{R}_{a}}.
\]

To asymptotically track constant reference inputs, we require an additional pole at the origin. For instance, the controller with transfer-function \( K\left( s\right)  = K/s \) achieves the design goal. The corresponding loop transfer-function is

\[
L\left( s\right)  = \frac{\beta }{s\left( {s + \alpha }\right) }.
\]

The corresponding Bode plots and Nyquist diagram are provided in Figure G.20. As seen in the Nyquist diagram in Figure G.18, no point on the negative real axis is encircled. Given that the open-loop transfer function has no poles in the right-hand plane, this guarantees asymptotic stability for any \( K > 0 \) . Selecting a \( K = 1 \) , we get a gain margin of infinity and a phase margin of 20.4 degrees.

## Teaching Points

1. DC motor dynamics can be reduced to first-order models.
2. Integral control is required for zero steady-state error to step references.
3. System type determines steady-state tracking performance.
4. Bode plots provide quantitative robustness measures.
5. Nyquist criterion gives a global stability guarantee.
6. Infinite gain margin indicates robustness to gain variations.
7. Phase margin reflects tolerance to unmodeled dynamics and delays.
