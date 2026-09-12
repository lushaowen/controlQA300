# Solution

## Method
\[
G\left( s\right)  = \frac{{b}_{2}s + {k}_{2}}{\left( {{m}_{2}{s}^{2} + {b}_{2}s + {k}_{2}}\right) \left( {{m}_{1}{s}^{2} + \left( {{b}_{1} + {b}_{2}}\right) s + {k}_{1} + {k}_{2}}\right)  - {\left( {b}_{2}s + {k}_{2}\right) }^{2}},
\]

which we assume to be asymptotically stable. Therefore, the steady state response to a constant force \( {f}_{2}\left( t\right)  = \; {\widetilde{f}}_{2} \) is given by

\[
{X}_{1\mathrm{{ss}}}\left( t\right)  = G\left( {j0}\right) \widetilde{f} = \frac{{k}_{2}\widetilde{f}}{{k}_{2}\left( {{k}_{1} + {k}_{2}}\right)  - {k}_{2}^{2}} = \frac{\widetilde{f}}{{k}_{1} + {k}_{2} - {k}_{2}} = \frac{\widetilde{f}}{{k}_{1}}.
\]

In equilibrium with a constant force \( {f}_{2} = \widetilde{f} \) applied at the mass \( {m}_{2} \) we shall have

\[
0 = \left( {{k}_{1} + {k}_{2}}\right) {x}_{1} - {k}_{2}{x}_{2} = {k}_{2}\left( {{x}_{1} - {x}_{2}}\right)  + {k}_{1}{x}_{1},\;
{k}_{2}\left( {{x}_{2} - {x}_{1}}\right)  = \widetilde{f}
\]

or

\[
{k}_{1}{x}_{1} = \widetilde{f}\; \Rightarrow  \;{x}_{1} = \frac{\widetilde{f}}{{k}_{1}},
\]

as predicted.

## Teaching Points
1. Relationship between frequency response and steady-state behavior
2. Use of DC gain to evaluate constant-input responses
3. Distinction between transient and steady-state effects of damping
4. Consistency between control-theoretic analysis and static force balance
5. Physical interpretation of equilibrium in coupled mechanical systems
