# Solution

## Method

We recall from P6.17 that,

\[
G_{1}(s) = \frac{Y(s)}{F_{1}(s)} = \frac{0.1s + 2}{s^{4} + 0.3s^{3} + 5.01s^{2} + 0.3s + 2},
\]

\[
G_{2}(s) = \frac{Y(s)}{F_{2}(s)} = \frac{s^{2} + 0.2s + 3}{s^{4} + 0.3s^{3} + 5.01s^{2} + 0.3s + 2},
\]

which have two pairs of complex conjugate poles in the open left-half plane. In order to analyze the impact of a constant disturbance \( f_{1} \) we shall first note that

\[
G_{1}(s) = T(s)G_{2}(s), \quad T(s) = \frac{0.1(s + 20)}{s^{2} + 0.2s + 3},
\]

where \( T(s) \) is asymptotically stable. Therefore, the transfer function from the disturbance force \( f_{1} \) to the closed-loop output \( y \) is given by

\[
T(s)D(s) = T(s)G_{2}(s)S(s).
\]

Since \( T(s) \) does not have a pole at the origin, asymptotic rejection of a constant disturbance will occur if \( D(s) \) has a zero at the origin, which is achieved by selecting a controller with a pole at the origin.

With

\[
K(s) = \frac{K(s + z)}{s},
\]

the resultant loop transfer function becomes

\[
L(s) = \frac{(s + z)G_{2}(s)}{s} = \frac{(s + z)(s^{2} + 0.2s + 3)}{s(s^{4} + 0.3s^{3} + 5.01s^{2} + 0.3s + 2)}.
\]

This loop transfer function has four complex stable poles and one pole at the origin, two complex stable zeros, and one real zero at \( -z \). Choosing a small value such as \( z = 0.05 \) ensures favorable asymptotic behavior.

From the Nyquist diagrams, no encirclement of the negative real axis is observed. Since the open-loop system has no poles in the right-half plane, closed-loop asymptotic stability is guaranteed for any \( K > 0 \). Selecting \( K = 1 \), the resulting gain margin is infinite and the phase margin is approximately \( 2.85^\circ \).

## Teaching Points

1. Modeling multi-degree-of-freedom mechanical systems using transfer functions
2. Interpretation of disturbance rejection in the frequency domain
3. Necessity of integral action for eliminating steady-state errors
4. Use of pole-zero analysis to guide controller design
5. Application of the Nyquist criterion to higher-order systems
6. Interpretation of small phase margins and robustness implications
