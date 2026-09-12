# Solution

We compute each partial fraction expansion by identifying the pole structure and applying
standard decomposition techniques. Polynomial division is performed when required.

---

## Method

### (a)–(d): Distinct Linear Poles

**(a)**
\[
\frac{1}{(s+1)(s+2)}
= \frac{1}{s+1} - \frac{1}{s+2}.
\]

**(b)**
\[
\frac{s-1}{(s+1)(s+2)}
= \frac{3}{s+2} - \frac{2}{s+1}.
\]

**(c)**
\[
\frac{s(s-1)}{(s+1)(s+2)}
= 1 + \frac{2}{s+1} - \frac{6}{s+2}.
\]

**(d)**
\[
\frac{s^2-1}{(s+1)(s+2)}
= 1 - \frac{3}{s+2}.
\]

---

### (e)–(f): Improper Rational Functions

**(e)**  
Performing polynomial division:
\[
\frac{s^2(s-1)}{(s+1)(s+2)}
= s - 4 - \frac{2}{s+1} + \frac{12}{s+2}.
\]

**(f)**
\[
\frac{1}{s(s+1)(s+2)}
= \frac{1}{2s} - \frac{1}{s+1} + \frac{1}{2(s+2)}.
\]

---

### (g)–(h): Repeated Poles

**(g)**
\[
\frac{1}{s^2(s+1)}
= \frac{1}{s^2} - \frac{1}{s} + \frac{1}{s+1}.
\]

**(h)**
\[
\frac{s-1}{s^2(s+1)}
= \frac{2}{s} - \frac{1}{s^2} - \frac{2}{s+1}.
\]

---

### (i)–(l): Quadratic and Complex Poles

**(i)**  
Since $s^2+2s+1=(s+1)^2$,
\[
\frac{1}{s^2+2s+1}
= \frac{1}{(s+1)^2}.
\]

**(j)**
\[
\frac{s}{(s+1)^2}
= \frac{1}{s+1} - \frac{1}{(s+1)^2}.
\]

**(k)**  
Using $s^2+2s+2=(s+1)^2+1$,
\[
\frac{1}{s^2+2s+2}
= \frac{j}{2\,[s+(1+j)]}
-\frac{j}{2\,[s+(1-j)]}.
\]

**(l)**
\[
\frac{s+1}{(s^2+2s+2)^2}
= \frac{1}{2\,[s+(1+j)]}
+\frac{1}{2\,[s+(1-j)]}.
\]

---

## Teaching Points

1. Always perform polynomial division for improper rational functions
2. Distinct linear poles lead to simple first-order terms
3. Repeated poles introduce higher-order denominators
4. Quadratic factors without real roots yield complex conjugate poles
5. Partial fraction expansion is essential for inverse Laplace transforms
