# Solution

## Method

In response to a constant ambient temperature, \( T_{o}(t) = \widetilde{T}_{o} \), a constant inflow temperature,
\( T_{i}(t) = \widetilde{T}_{i} \), and a constant heat source,
\( q(t) = \widetilde{q} \), the Laplace transform of the temperature, \( T(s) \), is:

\[
T(s) = G_q(s) Q(s) + G_i(s) T_i(s) + G_o(s) T_o(s)
\]

\[
= \frac{\beta}{s + \alpha}\frac{\widetilde{q}}{s}
+\frac{wc\beta}{s + \alpha}\frac{\widetilde{T}_i}{s}
+\frac{\beta / R}{s + \alpha}\frac{\widetilde{T}_o}{s}
\]

\[
= \frac{\beta}{s + \alpha}
\frac{\widetilde{q} + wc\widetilde{T}_i + \frac{1}{R}\widetilde{T}_o}{s}.
\]

Expanding in partial fractions:

\[
T(s)
=\left( \widetilde{q} + wc\widetilde{T}_i + \frac{1}{R}\widetilde{T}_o \right)
\frac{\beta}{\alpha}
\left( \frac{1}{s} - \frac{1}{s + \alpha} \right)
\]

from which we can identify the transient and steady-state parts of the response:

\[
T_{\mathrm{tr}}(t)
=-\left( \widetilde{q} + wc\widetilde{T}_i + \frac{1}{R}\widetilde{T}_o \right)
\frac{\beta}{\alpha} e^{-\alpha t},
\]

\[
T_{\mathrm{ss}}(t)
= \left( \widetilde{q} + wc\widetilde{T}_i + \frac{1}{R}\widetilde{T}_o \right)
\frac{\beta}{\alpha}.
\]

## Teaching Points

1. Superposition principle in linear thermal systems.
2. Step-response analysis of first-order thermodynamic models.
3. Interpretation of exponential decay as thermal transient behavior.
4. Physical meaning of steady-state temperature under constant inputs.
5. Influence of heat input, flow temperature, and ambient temperature on equilibrium.
