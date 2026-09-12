# Solution

## Method

For \( w = 0 \) , we have

\[
G\left( s\right)  = \frac{\beta }{s + \alpha },\;\alpha  = \frac{1}{Rmc},\;\beta  = \frac{1}{mc}.
\]

To ensure asymptotic tracking of constant reference inputs, we require a controller pole at the origin, say \( K\left( s\right)  = {K}_{p}/s \) . The corresponding loop transfer-function is:

\[
L = \frac{G}{s} = \frac{\beta }{s\left( {s + \alpha }\right) }
\]

with poles at \( \{  - \alpha ,0\} \) and no zeros. The corresponding Bode diagrams and Nyquist plots are shown in Figure G.22. As seen in the Nyquist diagram, no point on the negative real axis is encircled. Given that the open-loop transfer function has no poles in the right-hand plane, this guarantees asymptotic stability for any \( K > 0 \) . Selecting a \( K = 1 \) , we get a gain margin of infinity and a phase margin of 0.238 degrees.

## Teaching Points

1. Thermal systems can often be modeled as first-order dynamics.
2. Integral control is required for zero steady-state error to constant temperature references.
3. Frequency-domain analysis applies to thermal as well as mechanical systems.
4. Nyquist criterion provides a global stability guarantee.
5. Very small phase margins indicate limited robustness.
6. Infinite gain margin does not imply high robustness if phase margin is small.
7. Physical interpretation of controller design is essential in thermal systems.
