# Solution

## Method

The nonlinear differential equation in closed-loop is

For \( {x}_{1} = \theta ,{x}_{2} = \dot{\theta }, y = \theta \) , the closed-loop system can be described by the state-space realization

\[
\dot{x} = \left( \begin{matrix} {x}_{2} \\   - \frac{K}{{J}_{r}}{x}_{1} - \frac{mgr}{{J}_{r}}\sin {x}_{1} - \frac{b}{{J}_{r}}{x}_{2} + \frac{K}{{J}_{r}}r \end{matrix}\right) ,
\]

\[
y = {x}_{1}.
\]

Equilibrium implies \( {x}_{2} = {\bar{x}}_{2} = 0 \) and with \( r = \bar{r} = {\bar{x}}_{1} \) ,

\[
- \frac{K}{{J}_{r}}{\bar{x}}_{1} - \frac{mgr}{{J}_{r}}\sin {\bar{x}}_{1} + \frac{K}{{J}_{r}}\bar{r} = 0\; \Rightarrow  \;\sin {\bar{x}}_{1} = \sin \overline{\theta } = 0
\]

or \( \overline{\theta } = 0 \) or \( \overline{\theta } = \pi \) . Linearizing at \( \left( {\overline{\theta },\bar{r}}\right)  = \left( {0,0}\right) \) , we get

\[
\dot{\widetilde{x}} = \left\lbrack  \begin{matrix} 0 & 1 \\   - \frac{{mgr} + K}{{J}_{r}} &  - \frac{b}{{J}_{r}} \end{matrix}\right\rbrack  \widetilde{x} + \left\lbrack  \begin{matrix} 0 \\  \frac{K}{{J}_{r}} \end{matrix}\right\rbrack  \widetilde{r},
\]

\[
\widetilde{y} = \left\lbrack  \begin{array}{ll} 1 & 0 \end{array}\right\rbrack  \widetilde{x}
\]

with eigenvalues of the system matrix at

\[
\lambda  =  - \frac{b}{2{J}_{r}} \pm  \sqrt{\frac{{b}^{2}}{4{J}_{r}^{2}} - \frac{{mgr} + K}{{J}_{r}}},
\]

which lie in the open left-half plane for all \( K >  - {mgr} \) . Similarly, linearizing at \( \left( {\overline{\theta },\bar{r}}\right)  = \left( {\pi ,\pi }\right) \) , we have

\[
\dot{\widetilde{x}} = \left\lbrack  \begin{matrix} 0 & 1 \\  \frac{{mgr} - K}{{J}_{r}} &  - \frac{b}{{J}_{r}} \end{matrix}\right\rbrack  \widetilde{x} + \left\lbrack  \begin{matrix} 0 \\  \frac{K}{{J}_{r}} \end{matrix}\right\rbrack  \widetilde{r},
\]

\[
\widetilde{y} = \left\lbrack  \begin{array}{ll} 1 & 0 \end{array}\right\rbrack  \widetilde{x},
\]

with eigenvalues of the system matrix at

\[
\lambda  =  - \frac{b}{2{J}_{r}} \pm  \sqrt{\frac{{b}^{2}}{4{J}_{r}^{2}} - \frac{{mgr} - K}{{J}_{r}}},
\]

which lie in the open left-half plane for all \( K > {mgr} \) . That is, we stabilize both equilibrium points with this controller for all \( K > {mgr} \) .

## Teaching Points

1. Closed-loop nonlinear dynamics can preserve equilibrium locations.
2. Linearization reveals fundamentally different stability properties at different equilibria.
3. Proportional feedback can stabilize nonlinear systems locally.
4. Upright equilibrium stabilization requires sufficient control authority.
5. Gain selection must satisfy the most restrictive equilibrium condition.
