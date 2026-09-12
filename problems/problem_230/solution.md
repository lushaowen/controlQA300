# Solution

## Method

Substituting the data into our expression for the transfer function gives us the following

\[
\frac{T\left( s\right) }{{V}_{a}\left( s\right) } = \frac{s + {1.2749}}{s + {1.527}}.
\]

The open-loop system has a single pole at \( s =  - {1.527} \) . As we wish to achieve asymptotic tracking of a constant reference, we will start by considering the following controller

\[
K\left( s\right)  = \frac{{K}_{p}}{s}
\]

The corresponding Bode plots and Nyquist diagrams are provided in Figure G.21. As seen in the Nyquist diagram in Figure G.21, no point on the negative real axis is encircled. Given that the open-loop transfer function has no poles in the right-hand plane, this guarantees asymptotic stability for any \( K > 0 \) . Selecting a \( K = 1 \) , we get a gain margin of infinity and a phase margin of 90 degrees.

## Teaching Points

1. Torque control of DC motors can be formulated as a feedback control problem.
2. Integral control is necessary for zero steady-state error to constant references.
3. Pole-zero locations determine system type and tracking properties.
4. Bode plots provide quantitative measures of robustness.
5. Nyquist criterion offers a rigorous stability guarantee.
6. Infinite gain margin indicates insensitivity to loop gain variations.
7. A large phase margin implies strong robustness to unmodeled dynamics.
