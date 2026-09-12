# Solution

## Method


Because \( {e}^{-R\cos \theta } \) is even

\[
{\int }_{-\pi /2}^{\pi /2}{e}^{-R\cos \theta }{d\theta } = 2{\int }_{0}^{\pi /2}{e}^{-R\cos \theta }{d\theta },
\]

and use the hint to write for \( 0 \leq  \theta  \leq  \pi /2 \) that

\[
\cos \theta  \geq  1 - {2\theta }/\pi  \Rightarrow  {e}^{-R\cos \theta } \leq  {e}^{-R\left( {1 - {2\theta }/\pi }\right) }
\]

and

\[
{\int }_{-\pi /2}^{\pi /2}{e}^{-R\cos \theta }{d\theta } \leq  2{\int }_{0}^{\pi /2}{e}^{-R\left( {1 - {2\theta }/\pi }\right) }{d\theta } = \frac{\pi \left( {1 - {e}^{-R}}\right) }{R} < \frac{\pi }{R}
\]

for any \( R > 0 \) .


## Teaching Points
1. **Symmetry in Calculus**: Identifying even/odd functions can simplify integration limits and reduce potential calculation errors.
2. **Function Bounding**: Replacing a transcendental function (like $\cos \theta$) with a simpler linear bound is a standard technique for proving integral inequalities.
3. **Monotonicity**: Understanding that $e^x$ preserves inequality direction while multiplying by a negative number reverses it is crucial for rigorous proofs.
4. **Jordan's Inequality Context**: This specific cosine bound ($\cos \theta \geq 1 - 2\theta/\pi$) is the basis for Jordan's Lemma, frequently used in complex analysis and contour integration.