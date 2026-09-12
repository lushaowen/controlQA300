# Solution

## Method

The signals in Fig. 4.4b are such that

\[
y = \bar{y} + y
\]

which does not properly allow for one to uniquely determine \( y \) from the input signal \( \bar{y} \). The diagram is not well-posed.

One might develop some insight by placing a gain \( \alpha \) in the feedback path. In this case

\[
y = \bar{y} + \alpha y
\]

and

\[
(1 - \alpha) y = \bar{y}.
\]

When \( \alpha \neq 1 \)

\[
y = \frac{1}{1 - \alpha} \bar{y}.
\]

What happens when \( \alpha \rightarrow 1 \)?

## Teaching Points

1. Definition of well-posedness in feedback systems
2. Algebraic loops and signal ambiguity
3. Importance of causality in block-diagram representations
4. Role of feedback gains in resolving algebraic loops
5. Distinction between structural validity and stability
