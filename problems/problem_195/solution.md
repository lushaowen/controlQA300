# Solution

## Method

We have

\[
Y\left( s\right)  = G\left( s\right) U\left( s\right)  = \frac{{\omega }_{n}^{2}}{s\left( {s + \zeta {\omega }_{n} + j{\omega }_{d}}\right) \left( {s + \zeta {\omega }_{n} - j{\omega }_{d}}\right) },
\]

\[
= \frac{{\omega }_{n}^{2}/\left( {{\zeta }^{2}{\omega }_{n}^{2} + {\omega }_{d}^{2}}\right) }{s} - \frac{1}{2}\left( {\frac{{\omega }_{n}^{2}/\left( {{\omega }_{d}^{2} + {j\zeta }{\omega }_{n}{\omega }_{d}}\right) }{s + \zeta {\omega }_{n} - j{\omega }_{d}} + \frac{{\omega }_{n}^{2}/\left( {{\omega }_{d}^{2} - {j\zeta }{\omega }_{n}{\omega }_{d}}\right) }{s + \zeta {\omega }_{n} + j{\omega }_{d}}}\right)
\]

which by the residue formula yields

\[
y\left( t\right)  = \frac{{\omega }_{n}^{2}}{{\zeta }^{2}{\omega }_{n}^{2} + {\omega }_{d}^{2}} - \frac{1}{2}{e}^{-\zeta {\omega }_{n}t}\left( {\frac{{\omega }_{n}^{2}}{{\omega }_{d}^{2} + {j\zeta }{\omega }_{n}{\omega }_{d}}{e}^{j{\omega }_{d}t} + \frac{{\omega }_{n}^{2}}{{\omega }_{d}^{2} - {j\zeta }{\omega }_{n}{\omega }_{d}}{e}^{-j{\omega }_{d}t}}\right)
\]

\[
= 1 - \frac{{e}^{-\zeta {\omega }_{n}t}}{\sqrt{1 - {\zeta }^{2}}}\frac{1}{2j}\left( {{e}^{j\left( {\pi /2 - {\tan }^{-1}\left( \frac{\zeta }{\sqrt{1 - {\zeta }^{2}}}\right) }\right) }{e}^{j{\omega }_{d}t} + {e}^{-j\left( {-\pi /2 - {\tan }^{-1}\left( \frac{\zeta }{\sqrt{1 - {\zeta }^{2}}}\right) }\right) }{e}^{-j{\omega }_{d}t}}\right)
\]

\[
= 1 - \frac{{e}^{-\zeta {\omega }_{n}t}}{\sqrt{1 - {\zeta }^{2}}}\sin \left( {{\omega }_{d}t + \pi /2 - {\phi }_{d}}\right)
\]

for \( t \geq  0 \) .

## Teaching Points

1. Relationship between pole locations and time-domain response characteristics.
2. Use of Laplace transforms to compute step responses of LTI systems.
3. Interpretation of complex conjugate poles as damped oscillations.
4. Conversion from complex exponentials to sinusoidal expressions with phase shift.
5. Physical meaning of damping ratio, damped natural frequency, and transient decay.
