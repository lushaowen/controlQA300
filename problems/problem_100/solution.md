# Solution


## Method

Assuming zero initial conditions we calculate

\[
\left( {\left( {{J}_{1}{r}_{2}^{2} + {J}_{2}{r}_{1}^{2}}\right) s + \left( {{b}_{1}{r}_{2}^{2} + {b}_{2}{r}_{1}^{2}}\right) }\right) {\Omega }_{1}\left( s\right)  =
\]

\[
\left( {{J}_{1}{r}_{2}^{2} + {J}_{2}{r}_{1}^{2}}\right) \mathcal{L}\left\{  {\dot{\omega }}_{1}\right\}   + \left( {{b}_{1}{r}_{2}^{2} + {b}_{2}{r}_{1}^{2}}\right) \mathcal{L}\left\{  {\omega }_{1}\right\}   = {r}_{2}^{2}\mathcal{L}\{ \tau \}  = {r}_{2}^{2}T\left( s\right) ,
\]

and

\[
{\Omega }_{2}\left( s\right)  = \mathcal{L}\left\{  {\omega }_{2}\right\}   = \frac{{r}_{1}}{{r}_{2}}\mathcal{L}\left\{  {\omega }_{1}\right\}   = \frac{{r}_{1}}{{r}_{2}}{\Omega }_{1}\left( s\right)
\]

from which

\[
{\Omega }_{2}\left( s\right)  = G\left( s\right) T\left( s\right) ,\;G\left( s\right)  = \frac{\beta }{s + \alpha },
\]

where

\[
\alpha  = \frac{{b}_{1} + {b}_{2}{\left( {r}_{1}/{r}_{2}\right) }^{2}}{{J}_{1} + {J}_{2}{\left( {r}_{1}/{r}_{2}\right) }^{2}},\;\beta  = \frac{{r}_{1}/{r}_{2}}{{J}_{1} + {J}_{2}{\left( {r}_{1}/{r}_{2}\right) }^{2}}.
\]

From velocity to position we apply the integration property to obtain:

\[
{\Theta }_{2}\left( s\right)  = \mathcal{L}\left\{  {\theta }_{2}\right\}   = \mathcal{L}\left\{  {{\int }_{0}^{t}{\omega }_{2}\left( \tau \right) {d\tau }}\right\}   = \frac{{\Omega }_{2}\left( s\right) }{s}
\]

and

\[
{\Theta }_{2}\left( s\right)  = \frac{{\Omega }_{2}\left( s\right) }{s} = H\left( s\right) U\left( s\right) ,\;H\left( s\right)  = \frac{G\left( s\right) }{s} = \frac{\beta }{s\left( {s + \alpha }\right) }
\]

If all constants are positive, \( G\left( s\right) \) is asymptotically stable but \( H\left( s\right) \) is not since \( s = 0 \) is one of its roots.


## Teaching Points
1. **Reflected Inertia and Damping**: This problem demonstrates how mechanical parameters from different shafts are "reflected" through gear or pulley ratios.
2. **First-Order Mechanical Systems**: Velocity in a system with damping and inertia typically follows first-order dynamics.
3. **The Effect of Integration**: Integrating a stable velocity signal results in a position signal that can grow without bound for a constant input, leading to marginal stability (a pole at the origin).
4. **Standard Form**: Converting complex rational expressions into the $1/(s+\alpha)$ form simplifies the analysis of time constants and stability.