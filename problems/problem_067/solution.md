# Solution



## Method

We seek to calculate

\[
{\int }_{-\infty }^{\infty }\delta \left( t\right) {dt} = \mathop{\lim }\limits_{{\sigma  \rightarrow  \infty }}{\int }_{-\sigma }^{\sigma }\mathop{\lim }\limits_{{\rho  \rightarrow  \infty }}\frac{\sin \left( {\rho t}\right) }{\pi t}{dt}
\]

\[
= \mathop{\lim }\limits_{{\rho  \rightarrow  \infty }}\mathop{\lim }\limits_{{\sigma  \rightarrow  \infty }}{\int }_{-\sigma }^{\sigma }\frac{\sin \left( {\rho t}\right) }{\pi t}{dt}
\]

\[
= 2\mathop{\lim }\limits_{{\rho  \rightarrow  \infty }}\mathop{\lim }\limits_{{\sigma  \rightarrow  \infty }}{\int }_{0}^{\sigma }\frac{\sin \left( {\rho t}\right) }{\pi t}{dt}
\]

\[
= 2\mathop{\lim }\limits_{{\rho  \rightarrow  \infty }}\operatorname{sign}\left( \rho \right) \frac{1}{2} = 1
\]

because \( \sin \left( {\rho t}\right) /t \) is even.

## Teaching Points

1. The Dirac delta function can be defined via limits of ordinary functions.
2. Even symmetry simplifies improper integrals significantly.
3. The sine integral plays a central role in delta-function analysis.
4. This proof avoids distribution theory while remaining rigorous.
5. The unit-area property is fundamental in systems and signal analysis.
