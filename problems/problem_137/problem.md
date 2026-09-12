# Problem

## Problem Description

Show that if \( \widetilde{K} \) is such that an internally stable controller
\[
K = \widetilde{K}{\left( 1 + \widetilde{K}D\right) }^{-1}
\]
internally stabilizes the system \( G \) in the standard feedback diagram from Fig. 4.20(a) then \( \widetilde{K} \) internally stabilizes both feedback diagrams in Figs. 4.22(a) and (b).

Conversely, if an internally stable controller
\[
\widetilde{K} = K{\left( 1 - KD\right) }^{-1}
\]
internally stabilizes any of the feedback diagrams in Figs. 4.22(a) and (b) then \( K \) internally stabilizes the system \( G \) in the standard diagram of Fig. 4.20(a).

Hint: Use P4.15.

## Subproblems

1. Recall the definition of internal stability for feedback systems.
2. Express the relationship between \( K \) and \( \widetilde{K} \) using the given transformations.
3. Show how substituting controller blocks leads to equivalent feedback diagrams.
4. Analyze the relationship between the error signals \( e \) and \( \widetilde{e} \).
5. Prove that boundedness of signals is preserved under diagram transformation.
6. Apply similar reasoning to establish the converse implication.

## Additional Information

- The controller \( D \) represents a dynamic block in the feedback path.
- All controllers are assumed to be internally stable unless stated otherwise.
- Figures 4.20 and 4.22 describe equivalent feedback interconnections.
- Problem P4.15 provides the key equivalence result between feedback diagrams.

## Constraints

- No pole-zero cancellation assumptions are required.
- The argument must rely on signal boundedness and diagram equivalence.
- Stability must be understood in the internal (not just input–output) sense.
- The proof should be diagrammatic and algebraic rather than numerical.
