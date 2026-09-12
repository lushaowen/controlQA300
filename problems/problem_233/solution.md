# Solution

## Method
Recall from P5.42 that \( R = {2.5182} \times  {10}^{7} \) . From this, we can compute \( \Omega  = {1.5856} \times  {10}^{-4} \) . Using the Matlab ss2tf command, we compute the following transfer function

\[
\frac{Y\left( s\right) }{U\left( s\right) } = \frac{{1.983} \times  {10}^{ - }7}{{s}^{3} - {1.863} \times  {10}^{-{20}}{s}^{2} + {2.517} \times  {10}^{-8}s + {1.64} \times  {10}^{-{67}}},
\]

which has poles at \( s = 0 \) and \( s =  \pm  {1.58666} \times  {10}^{-4} \) . Let’s start by first trying a propositional controller with \( K\left( s\right)  = {K}_{p} \) . As seen in the Bode and Nyquist diagrams in Figure G.24, there are two clockwise encirclements of the negative real axis for any \( {K}_{p} > 0 \) , so this controller will not work. To avoid these two clockwise encirclements as in Figure G.24, we can try the controller \( K\left( s\right)  = {K}_{p}{\left( s + {0.0001}\right) }^{2} \) which gives the Bode and Nyquist diagrams in Figure G.25. This controller however is not proper, so we need to add two poles without affecting the encirclements. One possible way to achieve this is with the controller

\[
K\left( s\right)  = {K}_{p}\frac{{\left( s + {0.0001}\right) }^{2}}{{\left( s + {0.001}\right) }^{2}},
\]

whose Bode plot and the negative real axis portion of the Nyquist plot are shown in Figure G.26. This is now a proper controller and indicates no encirclements of the negative real axis for \( {K}_{p} < {0.00578} \) .

## Teaching Points
1. Linearization of nonlinear orbital dynamics around equilibrium orbits.
2. Interpretation of marginally stable poles in orbital systems.
3. Limitations of proportional control for lightly damped dynamics.
4. Role of pole-zero shaping in frequency-domain controller design.
5. Use of Nyquist criterion for closed-loop stability verification.
6. Importance of controller properness in physical implementations.
7. Gain and phase margins as robustness measures.
