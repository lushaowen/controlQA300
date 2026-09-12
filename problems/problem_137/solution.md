# Solution

## Method

Substituting the blocks between \( \widetilde{e} \) and \( u \) by the controller

\[
K = \widetilde{K}\left( 1 + \widetilde{K}D\right)
\]

in Fig. 4.3b leads to the standard diagram from Fig. 4.1a. So if \( K \) and \( G \) are such that Fig. 4.1a is internally stable then \( \widetilde{K}, D \), and \( G \) are such that Fig. 4.3b is also internally stable because \( K \) itself is internally stable.

Internal stability means boundedness of all signals in the diagram and equivalence between the two diagrams in Fig. 4.3 follows from the fact that

\[
e = \widetilde{e} - Du
\]

\[
= \bar{y} - \widetilde{y} - Du
\]

\[
= \bar{y} - Gu - Du
\]

\[
= \bar{y} - y .
\]

The converse is similar since internal stability of any of the diagrams in Fig. 4.3b with an internally stable controller

\[
\widetilde{K} = K\left( 1 - KD\right)^{-1}
\]

is the same as internal stability of the standard diagram in Fig. 4.1a with a controller \( K \).

## Teaching Points

1. Definition and interpretation of internal stability.
2. Equivalence of feedback diagrams via controller transformations.
3. Role of auxiliary dynamic blocks in feedback paths.
4. Preservation of bounded signals under diagram substitution.
5. Use of algebraic signal relationships to prove stability equivalence.
6. Importance of bidirectional (if and only if) stability arguments.
