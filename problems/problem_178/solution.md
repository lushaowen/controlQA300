# Solution

## Method
Equilibrium is at \( \bar{T}, {\bar{u}}_{1}, {\bar{u}}_{2}, {\bar{u}}_{3} \), and \( {\bar{u}}_{4} \), such that

\[
0 = \frac{1}{mc}{\bar{u}}_{1} + \frac{1}{m}{\bar{u}}_{2}\left( {{\bar{u}}_{3} - \bar{T}}\right) + \frac{1}{mcR}\left( {{\bar{u}}_{4} - \bar{T}}\right)
\]

which implies

\[
\bar{T} = \frac{R{\bar{u}}_{1} + {cR}{\bar{u}}_{2}{\bar{u}}_{3} + {\bar{u}}_{4}}{1 + {cR}{\bar{u}}_{2}}
\]

The linearized model is

\[
A = {\left. {\partial }_{x}f\left( x, u\right) \right| }_{x = \bar{x}, u = \bar{u}}
= - {\left. \frac{{u}_{2}}{m} - \frac{1}{mcR}\right| }_{x = \bar{x}, u = \bar{u}}
= - \frac{1 + {cR}{\bar{u}}_{2}}{mcR}
\]

\[
B = {\left. {\partial }_{u}f\left( x, u\right) \right| }_{x = \bar{x}, u = \bar{u}}
= {\left. \left\lbrack \begin{array}{llll}
\frac{1}{mc} & \frac{{u}_{3} - T}{m} & \frac{{u}_{2}}{m} & \frac{1}{mcR}
\end{array} \right\rbrack \right| }_{x = \bar{x}, u = \bar{u}}
\]

\[
= \left\lbrack \begin{array}{llll}
\frac{1}{mc} & \frac{{\bar{u}}_{3} - \bar{T}}{m} & \frac{{\bar{u}}_{2}}{m} & \frac{1}{mcR}
\end{array} \right\rbrack
\]

\[
C = {\left. {\partial }_{x}g\left( x, u\right) \right| }_{x = \bar{x}, u = \bar{u}} = 1
\]

\[
D = {\left. {\partial }_{u}g\left( x, u\right) \right| }_{x = \bar{x}, u = \bar{u}} = 0
\]

which is associated with the transfer-function

\[
G\left( s\right)
= C{\left( sI - A\right) }^{-1}B
= \frac{1}{s + \frac{1 + {cR}{\bar{u}}_{2}}{mcR}}
\left\lbrack \begin{array}{llll}
\frac{1}{mc} &
\frac{{\bar{u}}_{3} - \bar{T}}{m} &
\frac{{\bar{u}}_{2}}{m} &
\frac{1}{mcR}
\end{array} \right\rbrack
\]

which is asymptotically stable assuming all constants are positive.

## Teaching Points
1. Computation of equilibrium points in nonlinear thermal systems
2. Linearization of nonlinear state-space equations with multiple inputs
3. Interpretation of Jacobian matrices in physical systems
4. Derivation of multi-input transfer functions
5. Stability analysis based on pole locations of linearized models
