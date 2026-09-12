# Solution


## Method
 We seek to verify that the function \( {g}_{\tau }\left( t\right) \) is such that

\[
y\left( t\right)  = {\int }_{{0}^{ - }}^{t}g\left( {t - \tau }\right) u\left( \tau \right) {d\tau } = u\left( {kT}\right) ,\;{kT} \leq  t < \left( {k + 1}\right) T,\;k \in  \mathbb{N}.
\]

Using the sifting property of the impulse as in P3.11 the choice of \( {g}_{\tau }\left( t\right) \) in the statement is such that

\[
y\left( t\right)  = {\int }_{{0}^{ - }}^{t}{g}_{\tau }\left( {t - \tau }\right) u\left( \tau \right) {d\tau } = {\int }_{{0}^{ - }}^{t}\delta \left( {{kT} - \tau }\right) u\left( \tau \right) {d\tau } = u\left( {kT}\right) ,
\]

for \( {kT} \leq  t < \left( {k + 1}\right) T, k \in  \mathbb{N} \) , which is the desired result.

---

## Teaching Points
1. **LTV Impulse Response**: Unlike LTI systems where $g(t, \tau) = g(t-\tau)$, linear time-varying systems require a kernel $g_\tau(t)$ that accounts for the absolute time of the input.
2. **Sifting Property Application**: This problem demonstrates how the delta function can be used to mathematically model the "sampling" action by selecting a specific value of the input signal.
3. **Causality in Integration**: Note that the integral is evaluated up to time $t$. If the sampling point $kT$ were greater than $t$, the output would be zero, consistent with the principle of causality.
4. **Mathematical Modeling of Hardware**: The delta function provides a rigorous way to describe the transition from continuous-time signals to the discrete values used in sampled-data systems.