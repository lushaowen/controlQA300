# Solution

## Method

Substitute \( \overline{\tau } = 0 \) and \( {\overline{\omega }}_{2} = {\overline{\omega }}_{3} = 0 \) to obtain \( f\left( {\overline{\omega },0}\right)  = 0 \) .

The linearized model is

\[
A = {\left. {\partial }_{x}f\left( x, u\right) \right| }_{x = \bar{x}, u = \bar{u}}
\]

\[
= {\left. \left( \begin{matrix} 0 & {x}_{3}\left( {{J}_{2}/{J}_{1} - {J}_{3}/{J}_{1}}\right) & {x}_{2}\left( {{J}_{2}/{J}_{1} - {J}_{3}/{J}_{1}}\right) \\  {x}_{3}\left( {{J}_{3}/{J}_{2} - {J}_{1}/{J}_{2}}\right) & 0 & {x}_{1}\left( {{J}_{3}/{J}_{2} - {J}_{1}/{J}_{2}}\right) \\  {x}_{2}\left( {{J}_{1}/{J}_{3} - {J}_{2}/{J}_{3}}\right) & {x}_{1}\left( {{J}_{1}/{J}_{3} - {J}_{2}/{J}_{3}}\right) & 0 \end{matrix}\right) \right| }_{x = \bar{x}, u = \bar{u}}
\]

\[
= \left\lbrack  \begin{matrix} 0 & 0 & 0 \\  0 & 0 & \Omega \left( {{J}_{3}/{J}_{2} - {J}_{1}/{J}_{2}}\right) \\  0 & \Omega \left( {{J}_{1}/{J}_{3} - {J}_{2}/{J}_{3}}\right) & 0 \end{matrix}\right\rbrack
\]

\[
B = {\left. {\partial }_{u}f\left( x, u\right) \right| }_{x = \bar{x}, u = \bar{u}}
\]

\[
= \left\lbrack  \begin{matrix} 1/{J}_{1} & 0 & 0 \\  0 & 1/{J}_{2} & 0 \\  0 & 0 & 1/{J}_{3} \end{matrix}\right\rbrack  ,
\]

\[
C = {\left. {\partial }_{x}g\left( x, u\right) \right| }_{x = \bar{x}, u = \bar{u}} = I
\]

\[
D = {\left. {\partial }_{u}g\left( x, u\right) \right| }_{x = \bar{x}, u = c\bar{u}} = 0
\]

Eigenvalues of \( A \) are the roots of

\[
0 = \det \left( {{sI} - A}\right)  = s\left( {{s}^{2} - {\Omega }^{2}{ab}}\right) ,\;a = {J}_{3}/{J}_{2} - {J}_{1}/{J}_{2},\;b = {J}_{1}/{J}_{3} - {J}_{2}/{J}_{3}
\]

If \( {J}_{2} < {J}_{1} < {J}_{3} \) then \( a > 0 \) and \( b > 0 \) . If \( {J}_{3} < {J}_{1} < {J}_{2} \) then \( a < 0 \) and \( b < 0 \) . In both cases

\[
{s}^{2} - {\Omega }^{2}{ab} = 0
\]

has real roots, one of which is

\[
s = \Omega \sqrt{ab} > 0,
\]

which means that the equilibrium is unstable. It means that a rigid body will not spin about its second largest moment of inertia for long.

## Teaching Points

1. Identification of equilibrium points in nonlinear rotational dynamics
2. Linearization of Euler’s rigid body equations
3. Use of Jacobian matrices in stability analysis
4. Relationship between eigenvalues and equilibrium stability
5. Role of principal moments of inertia in rigid body motion
6. Physical interpretation of mathematical instability
7. Connection to the intermediate axis (tennis racket) theorem
