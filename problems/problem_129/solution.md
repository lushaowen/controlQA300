# Solution

## Method

Because there are no pole-zero cancelations in the product \( GK \) and

\[
S = \frac{1}{1 + GK} = \frac{1}{1 + \frac{1}{s}} = \frac{s}{s + 1}, \quad
D = \frac{G}{1 + GK} = \frac{\frac{1}{s}}{1 + \frac{1}{s}} = \frac{1}{s + 1}
\]

has a pole at \( s = -1 \), \( S \) is asymptotically stable and the closed-loop is internally stable. Because \( D \) does not have a zero at \( s = 0 \) the closed-loop does not achieves asymptotic rejection of a constant input disturbance.

## Teaching Points

1. Difference between internal stability and disturbance rejection
2. Role of the disturbance transfer function in performance analysis
3. Importance of zeros at the origin for constant disturbance rejection
4. Interpretation of DC gain in disturbance attenuation
5. Use of sensitivity-related functions in feedback analysis
