# Solution

## Method

Because there are no pole-zero cancelations in the product \( GK \) and

\[
S = \frac{1}{1 + GK}
= \frac{1}{1 + \frac{(s + 1)^2}{s(s^2 + 1)}}
= \frac{s(s^2 + 1)}{s^3 + s^2 + 3s + 1},
\]

\[
D = GS = \frac{s^2 + 1}{s^3 + s^2 + 3s + 1}
\]

has poles at
\( s \approx \{ -0.36,\; -0.32 \pm 1.63j \} \),
\( S \) is asymptotically stable and the closed-loop is internally stable. Because
\( G \) has a pole at \( s = 0 \),
\( S \) has a zero at \( s = 0 \)
and the closed-loop does achieves asymptotic tracking of a constant input. Likewise, because
\( K \) has poles at \( s = \pm j \),
\( D \) has zeros at \( s = \pm j \)
and the closed-loop does achieves asymptotic rejection of a sinusoidal input disturbance with frequency
\( \omega = 1 \).

## Teaching Points

1. Internal model principle for reference tracking
2. Role of sensitivity zeros at the origin
3. Sinusoidal disturbance rejection via frequency-domain zeros
4. Relationship between controller poles and disturbance attenuation
5. Distinction between stability and performance objectives
