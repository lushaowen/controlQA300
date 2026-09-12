# Solution

## Method

The sensitivity function for the diagram in Fig. 4.3a is obtained as

\[
e = \bar{y} - y
\]

\[
= \bar{y} - (G + D)u
\]

\[
= \bar{y} - \widetilde{K}(G + D)e
\]

from which

\[
e = \left( 1 + \widetilde{K}(G + D) \right)^{-1} \bar{y}.
\]

Hence \( S \) is as shown in the problem statement.

Likewise, the sensitivity function for the diagram in Fig. 4.3b is obtained as

\[
e = \bar{y} - \widetilde{y} - Du
\]

\[
= \bar{y} - Gu - Du
\]

\[
= \bar{y} - \widetilde{K}(G + D)e
\]

from which

\[
e = \left( 1 + \widetilde{K}(G + D) \right)^{-1} \bar{y}.
\]

Hence \( S \) is the same as above.

From \( \widetilde{e} \) to \( u \) we calculate

\[
u = \widetilde{K} e
\]

\[
= \widetilde{K}(\widetilde{e} - Du)
\]

\[
= \widetilde{K}\widetilde{e} - \widetilde{K}Du
\]

from which

\[
u = \frac{\widetilde{K}}{1 + \widetilde{K}D} \widetilde{e}.
\]

This yields the equivalent controller

\[
K = \frac{\widetilde{K}}{1 + \widetilde{K}D}.
\]

## Teaching Points

1. Equivalence of different feedback realizations
2. Use of block-diagram algebra to derive sensitivity functions
3. Separation of plant dynamics and auxiliary dynamics
4. Controller reparameterization via feedback transformations
5. Structural insight into robust control architectures
