# Solution


## Method

First calculate

\[
{\begin{Vmatrix}{u}_{\sigma }\end{Vmatrix}}_{2}^{2} = {\int }_{{0}^{ - }}^{\infty }{u}_{\sigma }{\left( t\right) }^{2}{dt}
\]

\[
= \frac{1}{\parallel G{\parallel }_{2}^{2}}{\int }_{{0}^{ - }}^{\infty }g{\left( \sigma  - t\right) }^{2}{dt}
\]

\[
= \frac{1}{\parallel G{\parallel }_{2}^{2}}{\int }_{{0}^{ - }}^{\sigma }g{\left( \sigma  - t\right) }^{2}{dt}
\]

because \( g\left( t\right)  = 0, t < 0 \) . Likewise

\[
{\begin{Vmatrix}{u}_{\sigma }\end{Vmatrix}}_{2}^{2} = \frac{1}{\parallel G{\parallel }_{2}^{2}}{\int }_{{0}^{ - }}^{\sigma }g{\left( \sigma  - t\right) }^{2}{dt},\;\tau  = \sigma  - t,\;{d\tau } =  - {dt},
\]

\[
= \frac{1}{\parallel G{\parallel }_{2}^{2}}{\int }_{{0}^{ - }}^{\sigma }g{\left( \tau \right) }^{2}{d\tau }
\]

---

	Hence

\[
\mathop{\lim }\limits_{{\sigma  \rightarrow  \infty }}{\begin{Vmatrix}{u}_{\sigma }\end{Vmatrix}}_{2}^{2} = \mathop{\lim }\limits_{{\sigma  \rightarrow  \infty }}\frac{1}{\parallel G{\parallel }_{2}^{2}}{\int }_{{0}^{ - }}^{\sigma }g{\left( \tau \right) }^{2}{d\tau } = 1.
\]

	Furthermore

\[
y\left( t\right)  = {y}_{\sigma }\left( t\right)  = {\int }_{{0}^{ - }}^{\infty }g\left( {t - \tau }\right) {u}_{\sigma }\left( \tau \right) {d\tau } = \frac{1}{\parallel G{\parallel }_{2}}{\int }_{{0}^{ - }}^{\infty }g\left( {t - \tau }\right) g\left( {\sigma  - \tau }\right) {d\tau }
\]

	and

\[
\mathop{\sup }\limits_{{t \geq  0}}\left| {{y}_{\sigma }\left( t\right) }\right|  \geq  \left| {{y}_{\sigma }\left( \sigma \right) }\right|
\]

\[
\geq  \frac{1}{\parallel G{\parallel }_{2}}{\int }_{{0}^{ - }}^{\sigma }g{\left( \sigma  - \tau \right) }^{2}{d\tau } = \parallel G{\parallel }_{2}{\begin{Vmatrix}{u}_{\sigma }\end{Vmatrix}}_{2}^{2}
\]

	Finally

\[
\mathop{\sup }\limits_{{t \geq  0}}\left| {y\left( t\right) }\right|  \geq  \mathop{\lim }\limits_{{\sigma  \rightarrow  \infty }}\parallel G{\parallel }_{2}{\begin{Vmatrix}{u}_{\sigma }\end{Vmatrix}}_{2}^{2} = \parallel G{\parallel }_{2}.
\]


## Teaching Points

1. Constructed inputs can achieve equality in norm inequalities
2. The $L_2$ norm of an impulse response plays a key role in system energy amplification
3. Causality simplifies integral bounds in convolution
4. Tightness means the bound is not conservative
5. This result characterizes worst-case behavior of stable LTI systems
