# Solution

## Method

In response to a constant voltage

\[
V_o(s) = G(s)\frac{\widetilde{v}}{s}
= \frac{\widetilde{v}}{s}\frac{C_1}{C_2}\frac{s + \frac{1}{R C_1}}{s}
= \frac{\widetilde{v}\alpha (s + \beta)}{s^2},
\quad
\alpha = \frac{C_1}{C_2},
\;
\beta = \frac{1}{R C_1}.
\]

Expanding in partial fractions:

\[
V_o(s) = \widetilde{v}\alpha \left( \frac{1}{s} + \frac{\beta}{s^2} \right).
\]

Since all poles are imaginary the entire response is in steady state:

\[
v_{o,\mathrm{ss}}(t)
= \widetilde{v}\alpha (1 + \beta t)
= \widetilde{v}\frac{C_1}{C_2}\left(1 + \frac{t}{R C_1}\right).
\]

## Teaching Points

1. Response of LTI systems to step (constant) inputs.
2. Use of Laplace-domain analysis to compute time-domain responses.
3. Interpretation of poles at the origin and their effect on system behavior.
4. Distinction between transient and steady-state components.
5. Physical interpretation of ramp-like steady-state responses in circuits.
