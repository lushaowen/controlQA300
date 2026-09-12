# Solution


## Method

First note that

\[
{\int }_{{0}^{ - }}^{\infty }{p}_{\varepsilon }\left( \tau \right) {d\tau } = {\varepsilon }^{-1}{\int }_{{0}^{ - }}^{\varepsilon }{d\tau } = 1.
\]

Also

\[
\mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}{\int }_{{0}^{ - }}^{\infty }{p}_{\varepsilon }\left( \tau \right) {d\tau } = \mathop{\lim }\limits_{{\varepsilon  \rightarrow  0}}{\int }_{{0}^{ - }}^{\varepsilon }{p}_{\varepsilon }\left( \tau \right) {d\tau } = 1.
\]


## Teaching Points
1. **Area Conservation**: The pulse function $p_{\epsilon}(\tau)$ is constructed such that as its width ($\epsilon$) decreases, its height ($1/\epsilon$) increases proportionally, keeping the total area constant at 1.
2. **Dirac Delta Foundation**: This exercise demonstrates the fundamental property of the unit impulse function $\delta(t)$. As $\epsilon \to 0$, $p_{\epsilon}(\tau)$ approaches $\delta(\tau)$, which is characterized by having infinite height, zero width, and an integral of unity.
3. **Integration Limits**: The use of $0^{-}$ is a formal way to ensure that the entire "mass" of the pulse starting at zero is captured within the integration bounds.
4. **Independent of Parameter**: The definite integral of the pulse is independent of the parameter $\epsilon$, which is a crucial requirement for defining generalized functions.