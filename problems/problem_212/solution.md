# Solution

## Method

Using the linearity approach from Section 5.1 to handle the derivatives on the input, \( \ddot{y} \), one can construct a state-space model with state

\[
x = \left( \begin{array}{l} {x}_{1} \\ {x}_{2} \\ {x}_{3} \\ {x}_{4} \end{array} \right)
\]

and matrices:

\[
A = \left\lbrack  \begin{matrix}
0 & 1 & 0 & 0 \\
-{k}_{s}\left( {{m}_{s} + {m}_{u}}\right) /\left( {{m}_{s}{m}_{u}}\right) & - {b}_{s}\left( {{m}_{s} + {m}_{u}}\right) /\left( {{m}_{s}{m}_{u}}\right) & {k}_{u}/{m}_{u} & {b}_{u}/{m}_{u} \\
0 & 0 & 0 & 1 \\
{k}_{s}/{m}_{u} & {b}_{s}/{m}_{u} & - {k}_{u}/{m}_{u} & - {b}_{u}/{m}_{u}
\end{matrix}\right\rbrack,
\quad
B = \left\lbrack  \begin{array}{l} 0 \\ 0 \\ 0 \\ -1 \end{array}\right\rbrack
\]

where

\[
x = {\dot{x}}_{2} =  - \frac{{k}_{s}\left( {{m}_{s} + {m}_{u}}\right) }{{m}_{s}{m}_{u}}{x}_{1}
-\frac{{b}_{s}\left( {{m}_{s} + {m}_{u}}\right) }{{m}_{s}{m}_{u}}{x}_{2}
+\frac{{k}_{u}}{{m}_{u}}{x}_{3}
+\frac{{b}_{u}}{{m}_{u}}{x}_{4},
\]

\[
z = {\dot{x}}_{4} =
\frac{{k}_{s}}{{m}_{u}}{x}_{1}
+\frac{{b}_{s}}{{m}_{u}}{x}_{2}
-\frac{{k}_{u}}{{m}_{u}}{x}_{3}
-\frac{{b}_{u}}{{m}_{u}}{x}_{4}
-u
\]

from which

\[
x + z =  - \frac{{k}_{s}}{{m}_{s}}{x}_{1}
-\frac{{b}_{s}}{{m}_{s}}{x}_{2}
-u
\]

which correspond to the matrices

\[
C = \left\lbrack  \begin{array}{llll} - {k}_{s}/{m}_{s} & - {b}_{s}/{m}_{s} & 0 & 0 \end{array}\right\rbrack,
\quad
D = -1.
\]

We can now choose a set of parameters and compute the poles and thus damping and natural frequencies of the system using MATLAB. The following code computes the natural frequency and damping ratio of the dominant poles.

---

ms = 600;

mu = 40;

ku = 200000;

bu = 0;

ks = 29*17000

bs = 29*770

A = [0 1 0 0 ;
     - ks*(ms+mu)/(ms*mu), -bs*(ms+mu)/(ms*mu), ku/mu, bu/mu;
     0 0 0 1 ;
     ks/mu, bs/mu, -ku/mu, -bu/mu];

B = [0;0;0;-1];

C = [-ks/ms, -bs/ms, 0, 0];

D = -1;

sys = ss(A, B, C, D);

[wn, zeta] = damp(sys);

wn/2/pi

zeta

---

A close enough solution is \( {k}_{s} = {464},{000}, {b}_{s} = {22},{330} \).

## Teaching Points

1. Modeling road excitation through acceleration inputs
2. State-space formulation of multi-degree-of-freedom systems
3. Relationship between physical parameters and modal properties
4. Identification of dominant poles in higher-order systems
5. Practical parameter tuning using numerical tools
