# Solution

For each impulse response, the system is analyzed following the same steps:
1. Compute the transfer function \( G(s) \)
2. Determine pole locations and system order
3. Assess asymptotic stability
4. Compute the unit step response
5. Separate transient and steady-state components

Throughout this solution, the unit step input amplitude is \( \widetilde{u} = 1 \).

---

## Method

### (a) \( g(t) = e^{-2t} - e^{-t} \)

\[
G(s) = -\frac{1}{s^2 + 3s + 2}
\]

- Poles: \( \{-2, -1\} \)
- Order: 2
- Stability: Asymptotically stable

\[
y(t) = -\frac{1}{2}(1 - e^{-t})^2
\]

\[
y_{\mathrm{tr}}(t) = \frac{1}{2}(2e^{-t} - e^{-2t}), \quad
y_{\mathrm{ss}}(t) = -\frac{1}{2}
\]

---

### (b) \( g(t) = e^{t} - e^{-t} \)

\[
G(s) = \frac{2}{s^2 - 1}
\]

- Poles: \( \{1, -1\} \)
- Order: 2
- Stability: Unstable

\[
y(t) = e^{-t} + e^{t} - 2
\]

\[
y_{\mathrm{tr}}(t) = e^{-t}, \quad
y_{\mathrm{ss}}(t) = -2
\]

---

### (c) \( g(t) = -t e^{-2t} \)

\[
G(s) = -\frac{1}{(s + 2)^2}
\]

- Poles: \( \{-2, -2\} \)
- Order: 2
- Stability: Asymptotically stable

\[
y(t) = -\frac{1}{4}\left(1 - 2t e^{-2t} - e^{-2t}\right)
\]

\[
y_{\mathrm{tr}}(t) = \frac{1}{4}(2t e^{-2t} + e^{-2t}), \quad
y_{\mathrm{ss}}(t) = -\frac{1}{4}
\]

---

### (d) \( g(t) = e^{-t}\cos(t) \)

\[
G(s) = \frac{s + 1}{(s + 1)^2 + 1}
\]

- Poles: \( \{-1 \pm j\} \)
- Order: 2
- Stability: Asymptotically stable

\[
y(t) = \frac{1}{2}\left(1 + e^{-t}\sin t - e^{-t}\cos t\right)
\]

\[
y_{\mathrm{tr}}(t) = \frac{1}{2}e^{-t}(\sin t - \cos t), \quad
y_{\mathrm{ss}}(t) = \frac{1}{2}
\]

---

### (e) \( g(t) = e^{-t}(\cos t - \sin t) \)

\[
G(s) = \frac{s}{s^2 + 2s + 2}
\]

- Poles: \( \{-1 \pm j\} \)
- Order: 2
- Stability: Asymptotically stable

\[
y(t) = e^{-t}\sin t
\]

\[
y_{\mathrm{tr}}(t) = y(t), \quad
y_{\mathrm{ss}}(t) = 0
\]

---

### (f) \( g(t) = \cos(t + \pi/6) \)

\[
G(s) = \frac{\sqrt{3}s - 1}{2(s^2 + 1)}
\]

- Poles: \( \{\pm j\} \)
- Order: 2
- Stability: Not asymptotically stable

\[
y(t) = \frac{1}{2}(\sqrt{3}\sin t + \cos t - 1)
\]

\[
y_{\mathrm{tr}}(t) = 0, \quad
y_{\mathrm{ss}}(t) = y(t)
\]

---

### (g) \( g(t) = t\cos t \)

\[
G(s) = \frac{s^2 - 1}{(s^2 + 1)^2}
\]

- Poles: \( \{\pm j, \pm j\} \)
- Order: 4
- Stability: Not asymptotically stable

\[
y(t) = -1 + \cos t + t\sin t
\]

\[
y_{\mathrm{tr}}(t) = 0, \quad
y_{\mathrm{ss}}(t) = y(t)
\]

---

### (h) \( g(t) = \delta(t) + t e^{-t}\sin t \)

\[
G(s) = 1 + \frac{2(s + 1)}{(s^2 + 2s + 2)^2}
\]

- Poles: \( \{-1 \pm j\} \) (double)
- Order: 4
- Stability: Asymptotically stable

\[
y(t) = \frac{1}{2}\left\{[t(\sin t + \cos t) + \cos t](\sinh t - \cosh t) + 3\right\}
\]

\[
y_{\mathrm{tr}}(t) = \frac{1}{2}[t(\sin t + \cos t) + \cos t](\sinh t - \cosh t), \quad
y_{\mathrm{ss}}(t) = \frac{3}{2}
\]

---

### (i) \( g(t) = 1(t) - 1(t - 1) \)

\[
G(s) = \frac{1 - e^{-s}}{s}
\]

- No poles
- Stability: Asymptotically stable

\[
y(t) = t - t\,1(t - 1) + 1(t - 1)
\]

\[
y_{\mathrm{tr}}(t) = y(t) - 1(t), \quad
y_{\mathrm{ss}}(t) = 1(t)
\]

---

### (j) Piecewise Polynomial Impulse Response

\[
G(s) = \frac{e^{-2s}(e^s - 1)^2}{s^2}
\]

- No poles
- Stability: Asymptotically stable

\[
y(t) = \frac{1}{2}\left[(t - 2)^2 1(t - 2) - 2(t - 1)^2 1(t - 1) + t^2\right]
\]

\[
y_{\mathrm{tr}}(t) = y(t) - 1(t), \quad
y_{\mathrm{ss}}(t) = 1(t)
\]

---

## Teaching Points
1. Different impulse responses lead to fundamentally different stability properties
2. Pole locations completely determine asymptotic stability
3. Systems without poles may still be stable if the impulse response is absolutely integrable
4. Purely imaginary poles lead to sustained oscillations
5. Transient terms correspond to decaying or non-decaying homogeneous responses
6. The residue at \( s = 0 \) determines steady-state response to step inputs
