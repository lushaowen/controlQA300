# Solution


## Method


\[
\mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}{\int }_{{0}^{ - }}^{t}\left| {{\dot{p}}_{\varepsilon }\left( \tau \right) }\right| {d\tau } = \mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}{\int }_{{0}^{ - }}^{\varepsilon }\left| {{\dot{p}}_{\varepsilon }\left( \tau \right) }\right| {d\tau } + {\int }_{\varepsilon }^{2\varepsilon }\left| {{\dot{p}}_{\varepsilon }\left( \tau \right) }\right| {d\tau }
\]

\[
= \mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}\frac{1}{{\varepsilon }^{2}}\left( {{\int }_{{0}^{ - }}^{2\varepsilon }{d\tau }}\right)
\]

\[
= \mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}\frac{1}{{\varepsilon }^{2}}\frac{4{\varepsilon }^{2}}{2} = \frac{1}{2}\text{ . }
\]


## Teaching Points
1. **Total Variation**: The integral of the absolute value of a derivative is related to the Total Variation of the original function. For a pulse that gets infinitely tall ($1/\epsilon$) as it narrows, the total variation must diverge.
2. **Singularity of Doublets**: While the integral of $\dot{p}_{\epsilon}(\tau)$ is $0$ (net area), the integral of its absolute value is infinite in the limit. This highlights that the Dirac doublet $\dot{\delta}(t)$ is an even more singular object than the Dirac Delta $\delta(t)$.
3. **$L^1$ Norm Divergence**: In functional analysis, this shows that the sequence of functions representing the pulse derivative does not converge in the $L^1$ norm.
4. **Physical Interpretation**: This divergence implies that as we try to create an infinitely fast transition (a step or impulse), the "rate of change" involved becomes infinite in a way that its accumulated magnitude cannot be contained.