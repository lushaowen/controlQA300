# Solution

We compute the inverse Laplace transform of each function using standard transform
pairs, algebraic manipulation, and Laplace properties such as linearity and time shifting.

---

## Method

### (a) \( \frac{1}{s(s+1)} \)

Using partial fractions:
\[
\frac{1}{s(s+1)} = \frac{1}{s} - \frac{1}{s+1}
\]

Taking inverse Laplace:
\[
\mathcal{L}^{-1} = 1 - e^{-t}
\]

---

### (b) \( \frac{s-1}{s+1} \)

Rewrite:
\[
\frac{s-1}{s+1} = 1 - \frac{2}{s+1}
\]

Inverse Laplace:
\[
\delta(t) - 2e^{-t}
\]

---

### (c) \( \frac{s-1}{s(s+1)} \)

Partial fractions yield:
\[
\frac{s-1}{s(s+1)} = -\frac{1}{s} + \frac{2}{s+1}
\]

Thus:
\[
2e^{-t} - 1
\]

---

### (d) \( \frac{s}{(s+1)^2} \)

Rewrite:
\[
\frac{s}{(s+1)^2} = \frac{1}{s+1} - \frac{1}{(s+1)^2}
\]

Inverse Laplace:
\[
e^{-t}(1 - t)
\]

---

### (e) \( \frac{1}{s^2 - 1} \)

Factor denominator:
\[
\frac{1}{(s-1)(s+1)}
\]

Inverse Laplace:
\[
\frac{1}{2} e^{-t}(e^{2t} - 1)
\]

---

### (f) \( \frac{1}{s^2 (s+2)^2} \)

Using partial fractions and known transforms:
\[
\frac{1}{4} e^{-2t} \left(e^{2t}t + t - e^{2t} + 1\right)
\]

---

### (g) \( \frac{1}{(s+1)^2 + 1} \)

Using the standard form:
\[
\mathcal{L}^{-1} = -\frac{1}{2} i e^{(-1-i)t}(-1 + e^{2it})
\]

---

### (h) \( \frac{1 - e^{-s}}{s} \)

Using time-shift property:
\[
1(t) - 1(t-1)
\]

---

### (i) \( \frac{s+1 - e^{-s}}{s(s+1)} \)

Decompose into known parts:
\[
( e^{1-t} - 1 )1(t-1) + 1(t)
\]

---

### (j) \( \frac{1 + s + s^2}{(1+s)^3} \)

Using repeated poles:
\[
\frac{1}{2} e^{-t}(t^2 - 2t + 2)
\]

---

### (k)

Combining all terms:
\[
\frac{1}{2} e^{-t}(t^2 - 2t + 2)
\]

---

## Teaching Points

1. Partial fraction expansion is essential for inverse Laplace transforms
2. Repeated poles lead to polynomial terms multiplied by exponentials
3. Exponential terms \( e^{-as} \) correspond to time delays
4. Dirac delta functions arise from constant terms in the Laplace domain
5. Complex poles lead to oscillatory time-domain behavior
6. Mastery of Laplace transform tables significantly simplifies co
