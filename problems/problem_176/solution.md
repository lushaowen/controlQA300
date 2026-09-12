# Solution

## Method
Equilibrium is at \( \bar{h}, \bar{u} \), such that

\[
0 = \frac{1}{A}\bar{u} - \frac{{\rho }^{1/\alpha }{g}^{1/\alpha }}{RA}{\bar{h}}^{1/\alpha }
\;\Rightarrow\;
\bar{h} = \frac{{R}^{\alpha }}{\rho g}{\bar{u}}^{\alpha }.
\]

The linearized model when \( \alpha = 2 \) is

\[
A = {\left. {\partial }_{x}f\left( x, u\right) \right| }_{x = \bar{x}, u = \bar{u}}
= - {\left. \frac{\sqrt{\rho g}}{RA}{x}^{-1/2}\right| }_{x = \bar{x}, u = \bar{u}}
= - \frac{\sqrt{\rho g}}{RA}\frac{\sqrt{\rho g}}{R\bar{u}}
= - \frac{\rho g}{{R}^{2}A\bar{u}}
\]

\[
B = {\left. {\partial }_{u}f\left( x, u\right) \right| }_{x = \bar{x}, u = \bar{u}}
= {\left. \frac{1}{A}u\right| }_{x = \bar{x}, u = \bar{u}}
= \frac{1}{A}
\]

\[
C = {\left. {\partial }_{x}g\left( x, u\right) \right| }_{x = \bar{x}, u = \bar{u}} = 1
\]

\[
D = {\left. {\partial }_{u}g\left( x, u\right) \right| }_{x = \bar{x}, u = \bar{u}} = 0
\]

which is associated with the transfer-function

\[
G\left( s\right) = C{\left( sI - A\right) }^{-1}B
= \frac{1/A}{s + \frac{\rho g}{{R}^{2}A\bar{u}}}
\]

which is asymptotically stable assuming all constants are positive.

## Teaching Points
1. Determination of equilibrium points in nonlinear dynamical systems
2. Linearization of nonlinear state-space models using Jacobians
3. Relationship between state-space representations and transfer functions
4. Physical interpretation of stability in fluid systems
5. Use of linearized models for local stability analysis
