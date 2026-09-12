# Solution

## Method

We have

\[
\frac{d}{dt}y\left( t\right)  =  - \frac{{e}^{-\zeta {\omega }_{n}t}}{\sqrt{1 - {\zeta }^{2}}}\left( {{\omega }_{d}\cos \left( {{\omega }_{d}t + \pi /2 - {\phi }_{d}}\right)  - \zeta {\omega }_{n}\sin \left( {{\omega }_{d}t + \pi /2 - {\phi }_{d}}\right) }\right) ,
\]

which equals to zero when

\[
\tan \left( {{\omega }_{d}{t}_{d} + \pi /2 - {\phi }_{d}}\right)  = \frac{{\omega }_{d}}{\zeta {\omega }_{n}} = \frac{\sqrt{1 - {\zeta }^{2}}}{\zeta } = \frac{1}{\tan \left( {\phi }_{d}\right) },
\]

or \( {\omega }_{d}{t}_{d} + \pi /2 - {\phi }_{d} = \pi /2 - {\phi }_{d} + {k\pi } \) , for \( k = 0,1,\ldots \) The first peak corresponds to \( k = 1 \) , so that \( {t}_{d} = \pi /{\omega }_{d} \) , and

\[
{y}_{p} = y\left( {t}_{p}\right)  = 1 - \frac{{e}^{-{\zeta \pi }/\sqrt{1 - {\zeta }^{2}}}}{\sqrt{1 - {\zeta }^{2}}}\sin \left( {{3\pi }/2 - {\phi }_{d}}\right)
\]

\[
= 1 + \frac{{e}^{-{\zeta \pi }/\sqrt{1 - {\zeta }^{2}}}}{\sqrt{1 - {\zeta }^{2}}}\cos \left( {\phi }_{d}\right)
\]

\[
= 1 + \frac{{e}^{-{\zeta \pi }/\sqrt{1 - {\zeta }^{2}}}}{\sqrt{1 - {\zeta }^{2}}}\frac{1}{\sqrt{\frac{{\zeta }^{2}}{1 - {\zeta }^{2}} + 1}}
\]

\[
= 1 + {e}^{-{\zeta \pi }/\sqrt{1 - {\zeta }^{2}}}\text{ . }
\]

## Teaching Points
1. **Extrema via Differentiation:** The time of peak overshoot in a step response is found by setting the derivative of the output to zero.
2. **Trigonometric Solutions:** Solving \( \dot{y}(t)=0 \) involves solving a trigonometric equation of the form \( A\cos(\theta) - B\sin(\theta) = 0 \), which simplifies to \( \tan(\theta) = A/B \). The general solution is \( \theta = \arctan(A/B) + k\pi \).
3. **Identifying the First Peak:** For the underdamped step response, the first maximum (peak overshoot) occurs at \( k=1 \), corresponding to \( t_p = \pi / \omega_d \). The case \( k=0 \) typically gives the initial slope or a local extremum that is not the first peak.
4. **Peak Value Derivation:** Substituting \( t_p \) back into \( y(t) \) and using trigonometric identities (\( \sin(3\pi/2 - \phi) = -\cos(\phi) \), \( \cos(\phi_d) = \zeta \)) leads to the compact formula for peak overshoot: \( y_p = 1 + e^{-\zeta \pi / \sqrt{1-\zeta^2}} \).
5. **Physical Interpretation:** The peak time \( t_p \) is inversely proportional to the damped natural frequency \( \omega_d \), meaning systems with higher \( \omega_d \) (faster oscillations) peak sooner. The peak value \( y_p \) depends only on the damping ratio \( \zeta \); smaller \( \zeta \) leads to larger overshoot.

---
