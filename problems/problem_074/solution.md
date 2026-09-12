# Solution


## Method

 Here we have

\[
{\int }_{{0}^{ - }}^{\infty }{p}_{\varepsilon }{\left( \tau \right) }^{2}{d\tau } = {\int }_{{0}^{ - }}^{\varepsilon }{\varepsilon }^{-2}{d\tau } = {\left| \varepsilon \right| }^{-1}
\]

and therefore

\[
\mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}{\int }_{{0}^{ - }}^{\infty }{p}_{\varepsilon }{\left( \tau \right) }^{2}{d\tau } = \mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}{\left| \varepsilon \right| }^{-1} = \infty .
\]


## Teaching Points
1. **Area vs. Energy**: While the integral of $p_{\epsilon}(\tau)$ (the area) is constant at $1$, the integral of its square (often related to "energy" in signal processing) is $1/\epsilon$.
2. **Singularity of the Dirac Delta**: This result illustrates why the Dirac Delta function $\delta(t)$ is not a square-integrable function ($L^2$ function). In the limit, its "energy" becomes infinite, which is a key distinction from standard functions.
3. **Sensitivity to $\epsilon$**: As the pulse becomes narrower and taller, the squaring operation amplifies the height ($1/\epsilon^2$) much faster than the width ($\epsilon$) decreases, leading to divergence.
4. **Generalized Functions**: This proof helps students understand that the delta function must be treated as a distribution/generalized function rather than a traditional function that can be squared or manipulated using standard arithmetic in all contexts.