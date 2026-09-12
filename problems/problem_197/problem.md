# Problem

## Problem Description

Use the approximation \( {\omega }_{\mathrm{d}}t \approx  {2k\pi }, k \in  \mathbb{Z} \) , formula (6.6), and solve for \( y\left( {t}_{s}\right)  - 1 \approx \) 0.02 to establish the settling time approximate formula (6.10).

（6.6）：
\[y(t) = \mathcal{L}^{-1} \left\{ \frac{G(s)}{s} \right\} = 1 - \frac{1}{\sqrt{1 - \zeta^2}} e^{-\zeta \omega_n t} \sin(\omega_d t + \pi / 2 - \phi_d), \quad t \geq 0, \]
（6.10）：
\[t_s = \frac{\log(50)}{\zeta \omega_n} \approx \frac{3.9}{\zeta \omega_n}. \]

## Subproblems

1. Recall the standard step response expression for an underdamped second-order system.
2. Identify the oscillatory term governing the envelope of the transient response.
3. Apply the approximation \( \omega_d t \approx 2k\pi \) to isolate peak response values.
4. Express the deviation \( y(t_s) - 1 \) in terms of the exponential decay envelope.
5. Solve the resulting inequality for the settling time \( t_s \).
6. Interpret the resulting expression as an approximate settling time formula.

## Additional Information

- Formula (6.6) refers to the standard underdamped step response expression.
- The settling time is defined using a 2% steady-state error criterion.
- The approximation assumes that oscillatory effects are dominated by the exponential decay envelope.
- Higher-order terms and phase shifts are neglected for simplicity.

## Constraints

- The derivation should be approximate, not exact.
- Only the dominant exponential term should be retained.
- The result should be expressed explicitly in terms of system parameters.
- The approximation must be valid for underdamped systems.
