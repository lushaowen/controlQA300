# Solution

## Method

Eliminate \( {u}_{g},{u}_{k} \) and \( {y}_{g} \) :

\[
{\dot{x}}_{g} = {A}_{g}{x}_{g} + {B}_{g}{y}_{k}
\]

\[
{\dot{x}}_{k} = {A}_{k}{x}_{k} + {B}_{k}\left( {\bar{y} - y}\right)
\]

\[
y = {C}_{g}{x}_{g} + {D}_{g}{y}_{k}
\]

\[
{y}_{k} = {C}_{k}{x}_{k} + {D}_{k}\left( {\bar{y} - y}\right)
\]

Rearrange the last two equations as

\[
\left\lbrack  \begin{matrix} I &  - {D}_{g} \\  {D}_{k} & I \end{matrix}\right\rbrack  \left( \begin{matrix} y \\  {y}_{k} \end{matrix}\right)  = \left( \begin{matrix} {C}_{g}{x}_{g} \\  {C}_{k}{x}_{k} + {D}_{k}\bar{y} \end{matrix}\right)
\]

and solve for \( {y}_{k} \) and \( y \) :

\[
\left( \begin{matrix} y \\  {y}_{k} \end{matrix}\right)  = {\left\lbrack  \begin{matrix} I &  - {D}_{g} \\  {D}_{k} & I \end{matrix}\right\rbrack  }^{-1}\left( \begin{matrix} {C}_{g}{x}_{g} \\  {C}_{k}{x}_{k} + {D}_{k}\bar{y} \end{matrix}\right)
\]

\[
= \left\lbrack  \begin{matrix} {\left( I + {D}_{g}{D}_{k}\right) }^{-1} & {D}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1} \\   - {D}_{k}{\left( I + {D}_{g}{D}_{k}\right) }^{-1} & {\left( I + {D}_{k}{D}_{g}\right) }^{-1} \end{matrix}\right\rbrack  \left( \begin{matrix} {C}_{g}{x}_{g} \\  {C}_{k}{x}_{k} + {D}_{k}\bar{y} \end{matrix}\right)
\]

\[
= \left( \begin{array}{l} {\left( I + {D}_{g}{D}_{k}\right) }^{-1}{C}_{g}{x}_{g} + {D}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1}{C}_{k}{x}_{k} + {D}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1}{D}_{k}\bar{y} \\   - {D}_{k}{\left( I + {D}_{g}{D}_{k}\right) }^{-1}{C}_{g}{x}_{g} + {\left( I + {D}_{k}{D}_{g}\right) }^{-1}{C}_{k}{x}_{k} + {\left( I + {D}_{k}{D}_{g}\right) }^{-1}{D}_{k}\bar{y} \end{array}\right)
\]

Substitute back into the first two equations:

\[
{\dot{x}}_{g} = {A}_{g}{x}_{g} + {B}_{g}{y}_{k}
\]

\[
= {A}_{g}{x}_{g} - {B}_{g}{D}_{k}{\left( I + {D}_{g}{D}_{k}\right) }^{-1}{C}_{g}{x}_{g} + {B}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1}{C}_{k}{x}_{k} +
\]

\[
{B}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1}{D}_{k}\bar{y}
\]

\[
= \left( {{A}_{g} - {B}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1}{D}_{k}{C}_{g}}\right) {x}_{g} + {B}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1}{C}_{k}{x}_{k} +
\]

\[
{B}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1}{D}_{k}\bar{y},
\]

and

\[
{\dot{x}}_{k} = {A}_{k}{x}_{k} + {B}_{k}\bar{y} - {B}_{k}y
\]

\[
= {A}_{k}{x}_{k} + {B}_{k}\bar{y} - {B}_{k}{\left( I + {D}_{g}{D}_{k}\right) }^{-1}{C}_{g}{x}_{g} -
\]

\[
{B}_{k}{D}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1}{C}_{k}{x}_{k} - {B}_{k}{D}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1}{D}_{k}\bar{y}
\]

\[
= \left( {{A}_{k} - {B}_{k}{D}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1}{C}_{k}}\right) {x}_{k} -
\]

\[
{B}_{k}{\left( I + {D}_{g}{D}_{k}\right) }^{-1}{C}_{g}{x}_{g} - {B}_{k}\left( {{D}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1}{D}_{k} - I}\right) \bar{y}
\]

\[
= \left( {{A}_{k} - {B}_{k}{\left( I + {D}_{g}{D}_{k}\right) }^{-1}{D}_{g}{C}_{k}}\right) {x}_{k} - {B}_{k}{\left( I + {D}_{g}{D}_{k}\right) }^{-1}{C}_{g}{x}_{g} + {B}_{k}{\left( I + {D}_{g}{D}_{k}\right) }^{-1}\bar{y}
\]

The vectorized versions of these two equations produce \( A \) and \( B \) . Matrices \( C \) and \( D \) are obtained from

\[
y = {\left( I + {D}_{g}{D}_{k}\right) }^{-1}{C}_{g}{x}_{g} + {D}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1}{C}_{k}{x}_{k} + {D}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1}{D}_{k}\bar{y}
\]

obtained before.
 

## Teaching Points
1. Feedback interconnection of state-space systems
2. Elimination of internal algebraic variables
3. Handling of direct feedthrough terms in feedback
4. Use of block-matrix inversion identities
5. Extension of SISO results to MIMO systems
