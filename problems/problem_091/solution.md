# Solution

We evaluate each contour integral using **Cauchy’s Residue Theorem**:
\[
\int_{C} f(s)\, ds = 2\pi j \sum \text{Res}(f, s_k)
\]
where the sum is over all poles inside the unit circle \( |s| < 1 \).

---

## Method

### (a) \( f(s) = 1 - e^{-s} \)

- The function is **entire** (analytic everywhere).
- There are no poles inside or outside the contour.

**Result:**
\[
\int_C f(s)\, ds = 0
\]

---

### (b) \( f(s) = \dfrac{1 + e^{-s}}{s} \)

- Simple pole at \( s = 0 \) (inside the unit circle).
- Residue:
  \[
  \operatorname{Res}_{s=0} f(s) = \lim_{s \to 0} (1 + e^{-s}) = 2
  \]

**Result:**
\[
\int_C f(s)\, ds = 2\pi j \cdot 2 = 4\pi j
\]

---

### (c) \( f(s) = \dfrac{1}{s^2} \)

- Second-order pole at \( s = 0 \).
- The residue of \( 1/s^2 \) is zero.

**Result:**
\[
\int_C f(s)\, ds = 0
\]

---

### (d) \( f(s) = \dfrac{1}{s(s + \tfrac{1}{2})} \)

- Simple poles at:
  - \( s = 0 \) (inside)
  - \( s = -\tfrac{1}{2} \) (inside)
- Residues:
  \[
  \operatorname{Res}_{s=0} = \frac{1}{1/2} = 2,
  \quad
  \operatorname{Res}_{s=-1/2} = -2
  \]
- Sum of residues inside \( C \) is zero.

**Result:**
\[
\int_C f(s)\, ds = 0
\]

---

### (e) \( f(s) = \dfrac{s}{(s + \tfrac{1}{2})(s + 2)} \)

- Poles at:
  - \( s = -\tfrac{1}{2} \) (inside)
  - \( s = -2 \) (outside)
- Residue at \( s = -\tfrac{1}{2} \):
  \[
  \operatorname{Res} = \frac{-1/2}{(-1/2 + 2)} = -\frac{1}{3}
  \]

**Result:**
\[
\int_C f(s)\, ds = 2\pi j \left(-\frac{1}{3}\right) = -\frac{2\pi j}{3}
\]

---

### (f) \( f(s) = \dfrac{1}{s(s + \tfrac{1}{2})} \)

- Simple pole inside unit circle at \( s = 0 \).
- Residue:
  \[
  \operatorname{Res}_{s=0} = \frac{1}{1/2} = \frac{1}{2}
  \]

**Result:**
\[
\int_C f(s)\, ds = 2\pi j \cdot \frac{1}{2} = \pi j
\]

---

### (g) \( f(s) = \dfrac{1}{s^2 + \tfrac{1}{4}} \)

- Poles at:
  \[
  s = \pm \frac{j}{2}
  \]
- Both poles lie inside the unit circle.
- Residues:
  \[
  \operatorname{Res}_{s=j/2} = -j, \quad
  \operatorname{Res}_{s=-j/2} = j
  \]
- Sum of residues is zero.

**Result:**
\[
\int_C f(s)\, ds = 0
\]

---

## Teaching Points
1. Entire functions yield zero contour integrals over closed paths
2. Only poles **inside** the contour contribute to the integral
3. Multiple poles may cancel via residue summation
4. Higher-order poles do not always contribute nonzero residues
5. Residue Theorem simplifies complex contour integrals to algebraic sums
