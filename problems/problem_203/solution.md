# Solution

## Method

In this case, we have the nonlinear differential equation in closed-loop:

\[
{J}_{r}\ddot{\theta } + \left( {b + {K}_{d}}\right) \dot{\theta } + {mgr}\sin \theta  + {K}_{p}\theta  = {K}_{d}\dot{r} + {K}_{p}r.
\]

Representing this equation in state-space is trickier but, in this case, can be done as in Fig. 5.5, which results from the rearrangement:

\[
\ddot{\theta } = \frac{{K}_{d}}{{J}_{r}}\dot{r} - \frac{b + {K}_{d}}{{J}_{r}}\dot{\theta } + \frac{{K}_{p}}{{J}_{r}}r - \frac{mgr}{{J}_{r}}\sin \theta  - \frac{{K}_{p}}{{J}_{r}}\theta .
\]

The resulting equations are akin to (5.2):

\[
\dot{x} = \left( \begin{matrix} \frac{{K}_{d}}{{J}_{r}}r - \frac{b + {K}_{d}}{{J}_{r}}{x}_{1} + {x}_{2} \\  \frac{{K}_{p}}{{J}_{r}}r - \frac{mgr}{{J}_{r}}\sin {x}_{1} - \frac{{K}_{p}}{{J}_{r}}{x}_{1} \end{matrix}\right) ,
\]

\[
y = {x}_{1},
\]

with \( y = {x}_{1} = \theta \) . Equilibrium is now at \( {x}_{1} = \overline{\theta }, r = \bar{r} = \overline{\theta } \) and

\[
\frac{{K}_{p}}{{J}_{r}}\bar{r} - \frac{mgr}{{J}_{r}}\sin \overline{\theta } - \frac{{K}_{p}}{{J}_{r}}\overline{\theta } = 0\; \Rightarrow  \;\sin \overline{\theta } = 0
\]

or \( \overline{\theta } = 0 \) or \( \overline{\theta } = \pi \) as before. Likewise \( {x}_{2} = {\bar{x}}_{2} \) where

\[
{\bar{x}}_{2} = \frac{b + {K}_{d}}{{J}_{r}}\overline{\theta } - \frac{{K}_{d}}{{J}_{r}}\bar{r}
\]

Linearizing at \( \left( {\overline{\theta },\bar{r}}\right)  = \left( {0,0}\right) \) , we get

\[
\dot{\widetilde{x}} = \left\lbrack  \begin{matrix}  - \frac{b + {K}_{d}}{{J}_{r}} & 1 \\   - \frac{{mg}{J}_{r}}{{J}_{r}} + {K}_{p} & 0 \end{matrix}\right\rbrack  \widetilde{x} + \left\lbrack  \begin{matrix} \frac{{K}_{d}}{{J}_{r}} \\  \frac{{K}_{p}}{{J}_{r}} \end{matrix}\right\rbrack  \widetilde{r},
\]

\[
\widetilde{y} = \left\lbrack  \begin{array}{ll} 1 & 0 \end{array}\right\rbrack  \widetilde{x},
\]

with eigenvalues of the system matrix at \( {\lambda }_{1} = 0 \) and

\[
\lambda  =  - \frac{b + {K}_{d}}{2} \pm  \sqrt{\frac{{\left( b + {K}_{d}\right) }^{2}}{4} - \frac{{mgr} + {K}_{p}}{{J}_{r}}}
\]

This equilibrium point is stable for all \( {K}_{p} >  - {mgr} \) and \( {K}_{d} >  - b \) . Similarly, linearizing at \( \left( {\overline{\mathbf{\theta }},\bar{r}}\right)  = \left( {\mathbf{\pi },\mathbf{\pi }}\right) \) , we have

\[
\dot{\widetilde{x}} = \left\lbrack  \begin{matrix}  - \frac{b + {K}_{d}}{{J}_{r}} & 1 \\   - \frac{{K}_{p} - {J}_{mp}}{{J}_{r}} & 0 \end{matrix}\right\rbrack  \widetilde{x} + \left\lbrack  \begin{matrix} \frac{{K}_{d}}{{J}_{r}} \\  \frac{{K}_{p}}{{J}_{r}} \end{matrix}\right\rbrack  \widetilde{r},
\]

\[
\widetilde{y} = \left\lbrack  \begin{array}{ll} 1 & 0 \end{array}\right\rbrack  \widetilde{x},
\]

with eigenvalues of the system matrix at

\[
\lambda  =  - \frac{b + {K}_{d}}{2} \pm  \sqrt{\frac{{\left( b + {K}_{d}\right) }^{2}}{4} - \frac{{K}_{p} - {mgr}}{{J}_{r}}}
\]

the system components of which lie in the open left-half plane for all \( {K}_{p} > {mgr} \) and \( {K}_{d} >  - b \) . That is, we stabilize both equilibrium points with this controller for all \( {K}_{p} > {mgr} \) and \( {K}_{d} >  - b \) .

## Teaching Points
1. **Closed-Loop Nonlinear Dynamics:** Shows how a linear control law modifies the structure of a nonlinear plant's equation.
2. **Equilibrium Persistence:** Illustrates that the physical equilibrium points of a system (dictated by `sin θ̅ = 0`) are invariant to the addition of a linear feedback controller that vanishes at those points (`e=0`, `\dot{e}=0`).
3. **State-Space Linearization:** Demonstrates the standard procedure for linearizing a nonlinear state-space model about an equilibrium point using the Jacobian.
4. **Stability of Different Equilibria:** Highlights that linearizing about different equilibrium points yields different linear models (specifically, different constant terms in the characteristic equation).
5. **Gain Tuning for Global Objectives:** The analysis reveals that stabilizing multiple (or all) equilibria of a nonlinear system often imposes stricter conditions on controller gains than stabilizing a single operating point. Here, stabilizing the inherently unstable upright position (`θ=π`) dictates the minimum required proportional gain.