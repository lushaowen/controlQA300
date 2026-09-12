# Solution

## 
 (a) Labeling \( {x}_{2} \) as the output of the first integrator and \( {x}_{1} \) as the output of the second integrator:

\[
\left( \begin{array}{l} {\dot{x}}_{1} \\  {\dot{x}}_{2} \end{array}\right)  = \left\lbrack  \begin{array}{ll}  - 1 & 1 \\   - 1 & 0 \end{array}\right\rbrack  \left( \begin{array}{l} {x}_{1} \\  {x}_{2} \end{array}\right)  + \left\lbrack  \begin{array}{l} 2 \\  1 \end{array}\right\rbrack  u
\]

\[
y = \left\lbrack  \begin{array}{ll} 1 & 0 \end{array}\right\rbrack  \left( \begin{array}{l} {x}_{1} \\  {x}_{2} \end{array}\right)
\]

Comparing with (5.2):

\[
Y\left( s\right)  = \frac{{2s} + 1}{{s}^{2} + s + 1}U\left( s\right)
\]

since \( {a}_{1} = 1,{a}_{2} = 1,{b}_{0} = 0,{b}_{1} = 2,{b}_{2} = 1 \) .

(b) Labeling \( {x}_{1} \) as the output of the first integrator and \( {x}_{2} \) as the output of the second integrator:

\[
{\dot{x}}_{1} = u + {x}_{2}
\]

\[
{\dot{x}}_{2} = {x}_{1}
\]

\[
y = {x}_{2} + u + {x}_{2}
\]

from which

\[
\left( \begin{array}{l} {\dot{x}}_{1} \\  {\dot{x}}_{2} \end{array}\right)  = \left\lbrack  \begin{array}{ll} 0 & 1 \\  1 & 0 \end{array}\right\rbrack  \left( \begin{array}{l} {x}_{1} \\  {x}_{2} \end{array}\right)  + \left\lbrack  \begin{array}{l} 1 \\  0 \end{array}\right\rbrack  u
\]

\[
y = \left\lbrack  \begin{array}{ll} 0 & 2 \end{array}\right\rbrack  \left( \begin{array}{l} {x}_{1} \\  {x}_{2} \end{array}\right)  + u
\]

Comparing with (5.1):

\[
Y\left( s\right)  = \frac{{s}^{2} + 1}{{s}^{2} - 1}
\]

since \( {a}_{1} = 0,{a}_{2} =  - 1,{b}_{0} = 1,{b}_{1} = {a}_{1}{b}_{0} = 0,{b}_{2} = 2 + {a}_{2}{b}_{0} = 1 \) .

(c) Labeling \( {x}_{1} \) as the output of the top integrator and \( {x}_{2} \) as the output of the bottom integrator:

\[
{\dot{x}}_{1} = u - {x}_{1}
\]

\[
{\dot{x}}_{2} = u - 2{x}_{1}
\]

\[
y = {x}_{1} + {x}_{2}
\]

from which

\[
\left( \begin{array}{l} {\dot{x}}_{1} \\  {\dot{x}}_{2} \end{array}\right)  = \left\lbrack  \begin{matrix}  - 1 & 0 \\  0 &  - 2 \end{matrix}\right\rbrack  \left( \begin{array}{l} {x}_{1} \\  {x}_{2} \end{array}\right)  + \left\lbrack  \begin{array}{l} 1 \\  1 \end{array}\right\rbrack  u
\]

\[
y = \left\lbrack  \begin{array}{ll} 1 & 1 \end{array}\right\rbrack  \left( \begin{array}{l} {x}_{1} \\  {x}_{2} \end{array}\right)
\]

and

\[
Y\left( s\right)  = \left\lbrack  \begin{array}{ll} 1 & 1 \end{array}\right\rbrack  {\left\lbrack  \begin{matrix} s + 1 & 0 \\  0 & s + 2 \end{matrix}\right\rbrack  }^{-1}\left\lbrack  \begin{array}{l} 1 \\  1 \end{array}\right\rbrack
\]

\[
= \frac{1}{s + 1} + \frac{1}{s + 2} = \frac{{2s} + 3}{{s}^{2} + {3s} + 2}
\]

(d) Labeling the output of integrators in sequence:

\[
{\dot{x}}_{1} = u + {x}_{2}
\]

\[
{\dot{x}}_{2} = {x}_{1}
\]

\[
{\dot{x}}_{3} = {x}_{2}
\]

\[
{\dot{x}}_{4} = {x}_{3}
\]

\[
y = {x}_{2} - {x}_{4}
\]

from which

\[
\left( \begin{array}{l} {\dot{x}}_{1} \\  {\dot{x}}_{2} \\  {\dot{x}}_{3} \\  {\dot{x}}_{4} \end{array}\right)  = \left\lbrack  \begin{array}{llll} 0 & 1 & 0 & 0 \\  1 & 0 & 0 & 0 \\  0 & 1 & 0 & 0 \\  0 & 0 & 1 & 0 \end{array}\right\rbrack  \left( \begin{array}{l} {x}_{1} \\  {x}_{2} \\  {x}_{3} \\  {x}_{4} \end{array}\right)  + \left\lbrack  \begin{array}{l} 1 \\  0 \\  0 \\  0 \end{array}\right\rbrack  u
\]

\[
y = \left\lbrack  \begin{array}{llll} 0 & 1 & 0 &  - 1 \end{array}\right\rbrack  \left( \begin{array}{l} {x}_{1} \\  {x}_{2} \\  {x}_{3} \\  {x}_{4} \end{array}\right)
\]

and

\[
Y\left( s\right)  = \left\lbrack  \begin{array}{llll} 0 & 1 & 0 &  - 1 \end{array}\right\rbrack  {\left\lbrack  \begin{matrix} s &  - 1 & 0 & 0 \\   - 1 & s & 0 & 0 \\  0 &  - 1 & s & 0 \\  0 & 0 &  - 1 & s \end{matrix}\right\rbrack  }^{-1}\left\lbrack  \begin{array}{l} 1 \\  0 \\  0 \\  0 \end{array}\right\rbrack
\]

\[
= \left\lbrack  \begin{array}{llll} 0 & 1 & 0 &  - 1 \end{array}\right\rbrack  {\left\lbrack  \begin{matrix} \frac{s}{{s}^{2} - 1} & \frac{1}{{s}^{2} - 1} & 0 & 0 \\  \frac{1}{{s}^{2} - 1} & \frac{s}{{s}^{2} - 1} & 0 & 0 \\  \frac{-1}{{s}^{2} - {s}^{3}} & \frac{1}{{s}^{2} - 1} & \frac{1}{s} & 0 \\  \frac{1}{{s}^{4} - {s}^{2}} &  - \frac{1}{s - {s}^{3}} & \frac{1}{{s}^{2}} & \frac{1}{s} \end{matrix}\right\rbrack  }^{-1}\left\lbrack  \begin{array}{l} 1 \\  0 \\  0 \\  0 \end{array}\right\rbrack
\]

\[
= \frac{1}{{s}^{2} - 1} - \frac{1}{{s}^{2}\left( {{s}^{2} - 1}\right) } = \frac{{s}^{2} - 1}{{s}^{2}\left( {{s}^{2} - 1}\right) } = \frac{1}{{s}^{2}}
\]

Note the pole-zero cancellation!

## Teaching Points
1. Selection of state variables from integrator outputs
2. Systematic construction of state-space equations
3. Conversion from state-space form to transfer functions
4. Interpretation of pole-zero cancellations
5. Relationship between block-diagrams and mathematical models