# Solution

## Method
Equilibrium is at \( \bar{v},\bar{u} = mg \), such that

\[
0 = - \frac{b}{m}|\bar{v}| \bar{v} + g \Rightarrow \bar{v} = \sqrt{\frac{mg}{b}}.
\]

The linearized model is obtained by evaluating the Jacobian matrices at the equilibrium point:

\[
A = \left. \frac{\partial f(x,u)}{\partial x} \right|_{x=\bar{x},u=\bar{u}}
= -\left. \frac{2b}{m}x \right|_{x=\bar{x}}
= -\frac{2b}{m}\sqrt{\frac{mg}{b}}
= -2\sqrt{\frac{bg}{m}}
\]

\[
B = \left. \frac{\partial f(x,u)}{\partial u} \right|_{x=\bar{x},u=\bar{u}}
= \frac{1}{m}u
= g
\]

\[
C = \left. \frac{\partial g(x,u)}{\partial x} \right|_{x=\bar{x},u=\bar{u}} = 1
\]

\[
D = \left. \frac{\partial g(x,u)}{\partial u} \right|_{x=\bar{x},u=\bar{u}} = 0
\]

The associated transfer function is

\[
G(s) = C (sI - A)^{-1} B = \frac{g}{s + 2\sqrt{\frac{bg}{m}}}
\]

Since the pole of the transfer function lies in the left half-plane, the equilibrium point is asymptotically stable.

## Teaching Points
1. Identification of equilibrium points in nonlinear dynamical systems
2. Application of Jacobian-based linearization techniques
3. Interpretation of physical meaning of equilibrium velocity
4. Relationship between linearized state-space models and transfer functions
5. Stability analysis using pole locations of transfer functions
