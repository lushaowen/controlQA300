# Solution


## Method


\[
\mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}{\int }_{{0}^{ - }}^{t}f\left( {t - \tau }\right) {\dot{p}}_{\varepsilon }\left( \tau \right) {d\tau } = \mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}{\int }_{{0}^{ - }}^{\varepsilon }f\left( {t - \tau }\right) {\dot{p}}_{\varepsilon }\left( \tau \right) {d\tau } + {\int }_{\varepsilon }^{2\varepsilon }f\left( {t - \tau }\right) {\dot{p}}_{\varepsilon }\left( \tau \right) {d\tau }
\]

\[
= \mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}\frac{1}{{\varepsilon }^{2}}\left( {{\int }_{{0}^{ - }}^{\varepsilon }f\left( {t - \tau }\right) {d\tau } - {\int }_{\varepsilon }^{2\varepsilon }f\left( {t - \tau }\right) {d\tau }}\right)
\]

\[
= \mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}\frac{1}{{\varepsilon }^{2}}\left( {{\int }_{{0}^{ - }}^{\varepsilon }\left( {f\left( t\right)  - \tau \dot{f}\left( \xi \right) }\right) {d\tau } - {\int }_{\varepsilon }^{2\varepsilon }\left( {f\left( t\right)  - \tau \dot{f}\left( \xi \right) }\right) {d\tau }}\right)
\]

\[
= \mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}\frac{\dot{f}\left( \xi \right) }{{\varepsilon }^{2}}\left( {{\int }_{\varepsilon }^{2\varepsilon }{\tau d\tau } - {\int }_{{0}^{ - }}^{\varepsilon }{\tau d\tau }}\right)
\]

\[
= \mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}\frac{\dot{f}\left( \xi \right) }{{\varepsilon }^{2}}\left( {\frac{4{\varepsilon }^{2} - {\varepsilon }^{2}}{2} - \frac{{\varepsilon }^{2}}{2}}\right)
\]

\[
= \mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}\frac{\widehat{f}\left( \xi \right) }{{\varepsilon }^{2}}{\varepsilon }^{2}
\]

\[
= \dot{f}\left( t\right) ,
\]

since \( \xi  \rightarrow  t \) as \( \varepsilon  \rightarrow  0 \) .


## Teaching Points
1. **The Doublet Property**: The derivative of a pulse function approximates a "unit doublet" (the derivative of the Dirac Delta function). While $\delta(t)$ sifts the value of the function, $\dot{\delta}(t)$ sifts the value of its derivative.
2. **Order of Magnitude**: The $1/\epsilon^2$ scaling is necessary because the integral involves the first-order term $\tau$, requiring an extra $1/\epsilon$ factor compared to a standard unit pulse to maintain a non-zero limit.
3. **Symmetry in Convolution**: The cancellation of the $f(t)$ term occurs due to the anti-symmetry of $\dot{p}_{\epsilon}(\tau)$ (the positive and negative rectangular pulses have equal area).
4. **Relationship to $\delta(t)$**: Formally, this proves $\int f(t-\tau)\dot{\delta}(\tau)d\tau = f(t)*\dot{\delta}(t) = \dot{f}(t)$.