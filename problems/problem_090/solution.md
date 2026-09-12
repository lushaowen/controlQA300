# Solution

Using the formal derivative property and the assumption \( f(0^-) = 0 \),
the Laplace transform of the derivative is
\[
\mathcal{L}\{\dot{f}(t)\} = sF(s).
\]

Thus, for each case, we compute \( \mathcal{L}^{-1}\{sF(s)\} \).

---

## Method

### (a) \( F(s) = \frac{1}{s} \)

\[
sF(s) = 1
\]

\[
\dot{f}(t) = \delta(t)
\]

---

### (b) \( F(s) = \frac{1}{s+1} \)

\[
sF(s) = 1 - \frac{1}{s+1}
\]

\[
\dot{f}(t) = \delta(t) - e^{-t}
\]

---

### (c) \( F(s) = \frac{1}{s^2} \)

\[
sF(s) = \frac{1}{s}
\]

\[
\dot{f}(t) = 1
\]

---

### (d) \( F(s) = \frac{1}{(s+1)^2} \)

\[
sF(s) = \frac{s+1-1}{(s+1)^2}
\]

\[
\dot{f}(t) = -e^{-t}(t - 1)
\]

---

### (e) \( F(s) = \frac{s}{(s+1)^2} \)

\[
sF(s) = \frac{s^2}{(s+1)^2}
\]

\[
\dot{f}(t) = e^{-t}(\delta(t) + t - 2)
\]

---

### (f) \( F(s) = \frac{e^{-s}}{s} \)

\[
sF(s) = e^{-s}
\]

\[
\dot{f}(t) = \delta(t - 1)
\]

---

### (g) \( F(s) = \frac{e^{-s}}{s+1} \)

\[
sF(s) = e^{-s} \left(1 - \frac{1}{s+1}\right)
\]

\[
\dot{f}(t) = \big(\delta(t-1) - e^{1-t}\big)1(t-1)
\]

---

### (h) \( F(s) = \frac{1 - e^{-2\pi s}}{s^2 + 1} \)

\[
sF(s) = \frac{s(1 - e^{-2\pi s})}{s^2 + 1}
\]

\[
\dot{f}(t) = \big(1(t-2\pi) - 1\big)\big(-\cos(t)\big)
\]

---

### (i) \( F(s) = \frac{(1 - e^{-2\pi s})s}{s^2 + 1} \)

\[
sF(s) = \frac{s^2(1 - e^{-2\pi s})}{s^2 + 1}
\]

\[
\dot{f}(t) =
1(t-2\pi)\big(\sin(t) - \delta(t-2\pi)\big)
+ \delta(t) - \sin(t)
\]

---

## Discontinuities

Discontinuities in the original signal \( f(t) \) occur at all time instants
where \( \dot{f}(t) \) contains **Dirac delta impulses**.

These locations are:
- \( t = 0 \) (initial jump)
- \( t = 1 \)
- \( t = 2\pi \)

---

## Teaching Points

1. The Laplace derivative property avoids explicit time-domain integration
2. Impulses in \( \dot{f}(t) \) indicate jumps in \( f(t) \)
3. Time delays in \( F(s) \) shift impulses in time
4. Rational Laplace transforms encode smooth behavior
5. Discontinuity analysis is central in systems and signals
