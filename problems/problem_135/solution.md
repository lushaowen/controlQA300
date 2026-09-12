# Solution

## Method

Follow the diagram to write:

\[
\widehat{e} = \bar{y} - \left( y - e^{-s\tau} G u \right) - G u
\]

\[
= \bar{y} - G u
\]

\[
= \bar{y} - GK \widehat{e}
\]

Solving for \( \widehat{e} \):

\[
\widehat{e} = \left( 1 + GK \right)^{-1} \bar{y}.
\]

Likewise

\[
S = \frac{1}{1 + e^{-s\tau} \widehat{K} G}
\]

\[
= \frac{1}{1 + \frac{e^{-s\tau} KG}{1 + \left( 1 - e^{-s\tau} \right) GK}}
\]

\[
= \frac{1 + \left( 1 - e^{-s\tau} \right) GK}{1 + \left( 1 - e^{-s\tau} \right) GK + e^{-s\tau} KG}
\]

\[
= \frac{1 + \left( 1 - e^{-s\tau} \right) GK}{1 + GK}.
\]

One has to select \( K \) such that the roots of \( 1 + GK \) have negative real part for \( S \) to be asymptotically stable. Use the argument in P4.13 to show that this is enough for internal stability.

## Teaching Points

1. Separation of delay-free and delay-dependent dynamics
2. Role of auxiliary error signals in Smith predictor analysis
3. Importance of the polynomial \( 1 + GK \) for stability
4. Internal stability versus external performance
5. Design philosophy behind predictor-based controllers
