# Solution

## Method

In this case, with \( w \neq  0 \) , we have

\[
G\left( s\right)  = \frac{\beta }{s + \alpha },\;\alpha  = \frac{\bar{w}}{m} + \frac{1}{mcR},\;\beta  = \frac{1}{mc}.
\]

To ensure asymptotic tracking of a constant plus sinusoidal reference inputs, we require controller poles at \( s = 0 \) and \( s =  \pm  {j\omega } \) , say

\[
K\left( s\right)  = \frac{\left( {s + {z}_{1}}\right) \left( {s + {z}_{2}}\right) }{s\left( {{s}^{2} + {\omega }^{2}}\right) }
\]

The corresponding loop transfer-function is:

\[
L = \frac{G}{s} = \frac{\beta \left( {s + {z}_{1}}\right) \left( {s + {z}_{2}}\right) }{s\left( {s + \alpha }\right) \left( {{s}^{2} + {\omega }^{2}}\right) }
\]

with poles at \( \{  - \alpha ,0,{j\omega }, - {j\omega }\} \) and zeros at \( \left\{  {-{z}_{1}, - {z}_{2}}\right\} \) . The zeros can be chosen with small negative real part so as to lead to a pair of stable asymptotes. For example, \( {z}_{1} = {z}_{2} = \alpha /4 \) . As seen in the Nyquist diagram in Figure G.23, no point on the negative real axis is encircled for \( K > 0 \) . Given that the open-loop transfer function has no poles in the right-hand plane, this guarantees asymptotic stability for any \( K > 0 \) .

## Teaching Points

1. Time-varying flow introduces periodic disturbances into thermal systems.
2. The internal model principle governs disturbance rejection and tracking.
3. Sinusoidal tracking requires controller poles at imaginary-axis frequencies.
4. Controller zeros can be used to stabilize asymptotic behavior.
5. Nyquist plots remain applicable for higher-order loop dynamics.
6. Robust stability can be achieved despite periodic disturbances.
7. Linearization enables frequency-domain analysis of nonlinear effects.
