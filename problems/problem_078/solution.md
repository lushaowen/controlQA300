# Solution

## Method

\[
\mathop{\lim }\limits_{{\varepsilon \rightarrow 0}} \int_{{0}^{-}}^{t} \dot{p}_{\varepsilon}(\tau)^2 \, d\tau
= \mathop{\lim }\limits_{{\varepsilon \rightarrow 0}} \int_{{0}^{-}}^{\varepsilon} \dot{p}_{\varepsilon}(\tau)^2 \, d\tau
+\int_{\varepsilon}^{2\varepsilon} \dot{p}_{\varepsilon}(\tau)^2 \, d\tau
\]

\[
= \mathop{\lim }\limits_{{\varepsilon \rightarrow 0}} \frac{1}{\varepsilon^4}
\left( \int_{{0}^{-}}^{2\varepsilon} d\tau \right)
\]

\[
= \mathop{\lim }\limits_{{\varepsilon \rightarrow 0}} \frac{1}{\varepsilon^4}
\frac{4\varepsilon^2}{2}
= \mathop{\lim }\limits_{{\varepsilon \rightarrow 0}} \frac{2}{\varepsilon^2}
= \infty \, .
\]

## Teaching Points

1. Squared derivatives of impulse approximations can diverge
2. Importance of support width in regularized signals
3. Limits involving impulsive behavior require careful scaling analysis
4. Distinction between finite-energy and infinite-energy signals
5. Physical implications of divergent integrals in system modeling
