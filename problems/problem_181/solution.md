# Solution

## Method

For equilibrium with \( {\bar{u}}_{t} = {\bar{u}}_{r} = 0 \) :

so that

\[
{\bar{x}}_{3} = \sqrt{\frac{GM}{{\bar{x}}_{1}^{3}}},
\]

which is satisfied when \( {\bar{x}}_{1} = R,{\bar{x}}_{3} = \Omega \) , and \( {\Omega }^{2}{R}^{3} = {GM} \) .

The linearized model about

\[
\widehat{x} = \left( \begin{matrix} r - R \\  \dot{r} \\  \omega  - \Omega  \end{matrix}\right) ,\;\widehat{u} = \left( \begin{matrix} {u}_{r} \\  {u}_{t} \end{matrix}\right) ,\;\widehat{y} = r - R,
\]

is

\[
A = {\left. {\partial }_{x}f\left( x, u\right) \right| }_{x = \bar{x}, u = \bar{u}} = \left\lbrack  \begin{matrix} 0 & 1 & 0 \\  {\bar{x}}_{3}^{2} + 2\frac{GM}{{\bar{x}}_{1}^{3}} & 0 & 2{\bar{x}}_{1}{\bar{x}}_{3} \\  2\frac{{\bar{x}}_{2}{\bar{x}}_{3}}{{\bar{x}}_{1}^{2}} - \frac{{\bar{u}}_{1}}{{\bar{m}}_{1}^{2}} &  - 2\frac{{\bar{x}}_{3}}{{\bar{x}}_{1}} &  - 2\frac{{\bar{x}}_{2}}{{\bar{x}}_{1}} \end{matrix}\right\rbrack   = \left\lbrack  \begin{matrix} 0 & 1 & 0 \\  3{\Omega }^{2} & 0 & {2\Omega R} \\  0 &  - 2\frac{\Omega }{R} & 0 \end{matrix}\right\rbrack
\]

\[
B = {\left. {\partial }_{u}f\left( x, u\right) \right| }_{x = \bar{x}, u = \bar{u}} = \left\lbrack  \begin{matrix} 0 & 0 \\  \frac{1}{m} & 0 \\  0 & \frac{1}{m{\bar{x}}_{1}} \end{matrix}\right\rbrack   = \left\lbrack  \begin{matrix} 0 & 0 \\  \frac{1}{m} & 0 \\  0 & \frac{1}{Rm} \end{matrix}\right\rbrack  ,
\]

\[
C = {\left. {\partial }_{x}g\left( x, u\right) \right| }_{x = \bar{x}, u = \bar{u}} = \left\lbrack  \begin{array}{lll} 1 & 0 & 0 \end{array}\right\rbrack
\]

\[
D = {\left. {\partial }_{u}g\left( x, u\right) \right| }_{x = \bar{x}, u = c\bar{u}} = \left\lbrack  \begin{array}{ll} 0 & 0 \end{array}\right\rbrack
\]

Then perform the change of coordinates

\[
\widetilde{x} = \left( \begin{matrix} r - R \\  \dot{r} \\  R\left( {\omega  - \Omega }\right)  \end{matrix}\right)  = \left( \begin{matrix} 1 & 0 & 0 \\  0 & 1 & 0 \\  0 & 0 & R \end{matrix}\right) \widehat{x},\;\widetilde{u} = \widehat{u},\;\widetilde{y} = \widehat{y},
\]

to obtain

\[
\dot{\widetilde{x}} = \left\lbrack  \begin{matrix} 0 & 1 & 0 \\  3{\Omega }^{2} & 0 & {2\Omega } \\  0 &  - {2\Omega } & 0 \end{matrix}\right\rbrack  \widetilde{x} + \left\lbrack  \begin{matrix} 0 & 0 \\  0 & \frac{1}{m} \\  \frac{1}{m} & 0 \end{matrix}\right\rbrack  \widetilde{u},
\]

\[
\widetilde{y} = \left\lbrack  \begin{array}{lll} 1 & 0 & 0 \end{array}\right\rbrack  \widetilde{x}
\]

## Teaching Points

1. Identification of equilibrium conditions for circular orbital motion
2. Linearization of nonlinear gravitational dynamics
3. Use of Jacobian matrices in orbital mechanics
4. Interpretation of Coriolis and centripetal coupling terms
5. Coordinate transformations for improved physical interpretation
6. State-space modeling of orbital perturbations
7. Role of thrust inputs in orbital co
