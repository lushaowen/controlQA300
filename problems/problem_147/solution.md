# Solution

## Method

We have

\[
{v}_{a} = \frac{{R}_{a}}{{K}_{t}}\tau  + {K}_{e}\omega .
\]

Taking Laplace transforms:

\[
{V}_{a}\left( s\right)  = \frac{{R}_{a}}{{K}_{t}}T\left( s\right)  + {K}_{e}\Omega \left( s\right)
\]

so that

\[
T\left( s\right)  = \frac{{K}_{t}}{{R}_{a}}\left( {{V}_{a}\left( s\right)  - {K}_{e}\Omega \left( s\right) }\right)
\]

\[
\begin{array}{l}
= \frac{{K}_{t}}{{R}_{a}}\left( {{V}_{a}\left( s\right)  - \frac{\frac{{K}_{e}{K}_{t}}{J{R}_{a}}}{s + \frac{h}{J} + \frac{{K}_{e}{K}_{t}}{J{R}_{a}}}{V}_{a}\left( s\right) }\right)
\end{array}
\]

\[
= \frac{{K}_{t}}{{R}_{a}}\frac{s + \frac{b}{J} + \frac{{K}_{e}{K}_{t}}{J{R}_{a}} - \frac{{K}_{e}{K}_{t}}{J{R}_{a}}}{s + \frac{b}{J} + \frac{{K}_{e}{K}_{t}}{J{R}_{a}}}{V}_{a}\left( s\right)
\]

\[
= \frac{{K}_{t}}{{R}_{a}}\frac{s + \frac{b}{J}}{s + \frac{b}{J} + \frac{{K}_{e}{K}_{t}}{J{R}_{a}}}{V}_{a}\left( s\right)
\]

after substituting the transfer-function between \( \Omega \left( s\right) \) and \( {V}_{a}\left( s\right) \) calculated earlier.

## Teaching Points

1. Relationship between electrical and mechanical subsystems in DC motors
2. Elimination of intermediate variables to obtain input–output models
3. Interpretation of zeros introduced by mechanical dynamics
4. Effect of back electromotive force on torque generation
5. Cascaded modeling of electrical and mechanical dynamics
6. Importance of previously derived subsystem transfer functions
7. Physical meaning of pole–zero cancellation in electromechanical systems
