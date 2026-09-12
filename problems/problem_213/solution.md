# Solution

## Method
The first equation is the first equation in the result of P6.24 after multiplying by \( {m}_{s} \) and plugging in for \( u \) . The second equation is the second equation in the result of P6.24 after plugging in for \( u \) . Verification of these statements is left to the student.

Using the integration approach from Section 5.1 to handle the derivatives on the inputs, \( {u}_{1} = u,{u}_{2} = y \) , one can rearrange:

\[
\ddot{z} =  - \frac{{b}_{u}}{{m}_{u}}\dot{z} - \frac{{k}_{u}}{{m}_{u}}z - \frac{1}{{m}_{u}}{u}_{1} - {\ddot{u}}_{2}
\]

and integrate twice to obtain:

\[
z =  - {u}_{2} + \left( {\int  - \frac{{b}_{u}}{{m}_{u}}z+\int \left( {-\frac{{k}_{u}}{{m}_{u}}z - \frac{1}{{m}_{u}}{u}_{1}}\right) }\right)
\]

After defining the states \( {x}_{1},{x}_{2} \) to carry on the above integrations and noting that \( z = {x}_{1} - {u}_{2} \) one obtains:

\[
{\dot{x}}_{1} =  - \frac{{b}_{u}}{{m}_{u}}z + {x}_{2} =  - \frac{{b}_{u}}{{m}_{u}}{x}_{1} + {x}_{2} + \frac{{b}_{u}}{{m}_{u}}{u}_{2},
\]

\[
{\dot{x}}_{2} =  - \frac{{k}_{u}}{{m}_{u}}z - \frac{1}{{m}_{u}}{u}_{1} =  - \frac{{k}_{u}}{{m}_{u}}{x}_{1} - \frac{1}{{m}_{u}}{u}_{1} + \frac{{k}_{u}}{{m}_{u}}{u}_{2}.
\]

Similarly for the first equation

\[
\ddot{x} = \frac{{b}_{u}}{{m}_{u}}\dot{z} + \frac{{k}_{u}}{{m}_{u}}z + \left( {\frac{1}{{m}_{u}} + \frac{1}{{m}_{s}}}\right) {u}_{1}.
\]

and, after integration,

\[
x = \int \frac{{b}_{u}}{{m}_{u}}z + \int \left( {\frac{{k}_{u}}{{m}_{u}}z + \left( {\frac{1}{{m}_{u}} + \frac{1}{{m}_{s}}}\right) {u}_{1}}\right) .
\]

The choice of \( {x}_{3},{x}_{4} \) to carry the integration leads to

\[
{\dot{x}}_{3} = \frac{{b}_{u}}{{m}_{u}}z + {x}_{4} = \frac{{b}_{u}}{{m}_{u}}{x}_{1} + {x}_{4} - \frac{{b}_{u}}{{m}_{u}}{u}_{2},
\]

\[
{\dot{x}}_{4} = \frac{{k}_{u}}{{m}_{u}}z + \left( {\frac{1}{{m}_{u}} + \frac{1}{{m}_{s}}}\right) {u}_{1} = \frac{{k}_{u}}{{m}_{u}}{x}_{1} + \left( {\frac{1}{{m}_{u}} + \frac{1}{{m}_{s}}}\right) {u}_{1} - \frac{{k}_{u}}{{m}_{u}}{u}_{2},
\]

Putting these together one calculates a realization with matrices

\[
A = \left\lbrack  \begin{matrix}  - {b}_{u}/{m}_{u} & 1 & 0 & 0 \\   - {k}_{u}/{m}_{u} & 0 & 0 & 0 \\  {b}_{u}/{m}_{u} & 0 & 0 & 1 \\  {k}_{u}/{m}_{u} & 0 & 0 & 0 \end{matrix}\right\rbrack  ,\;
B = \left\lbrack  \begin{matrix} 0 & {b}_{u}/{m}_{u} \\   - 1/{m}_{u} & {k}_{u}/{m}_{u} \\  0 &  - {b}_{u}/{m}_{u} \\  1/{m}_{u} + 1/{m}_{s} &  - {k}_{u}/{m}_{u} \end{matrix}\right\rbrack
\]

where the output (for feedback) is

\[
x = {x}_{3}
\]

from which

\[
C = \left\lbrack  \begin{array}{llll} 0 & 0 & 1 & 0 \end{array}\right\rbrack ,\quad D = 0.
\]

Using MATLAB to calculate a transfer-function from \( {u}_{1} \) to \( x \) :

\[
G(s) = 0.026667 \frac{s^2 + 312.5}{s^2 (s^2 + 5000)}
\]

Proceeding as in P6.23, the connection corresponds to the PD controller

\[
K(s) = {b}_{s}(s + z), \quad z = \frac{{k}_{s}}{{b}_{s}}.
\]

Placing the open-loop zero at \( z = 20 \) yields a root-locus that meets the design objectives. A gain of approximately \( 2.6 \times 10^4 \) places the closed-loop poles at the desired natural frequency and damping ratio.
![alt text](images\image.png)
## Teaching Points
1. Interpretation of mechanical feedback as PD control
2. State-space realization via integration of second-order systems
3. Physical meaning of proportional and derivative actions in suspension control
4. Use of root-locus for controller parameter selection
5. Relationship between pole locations, damping ratio, and natural frequency
