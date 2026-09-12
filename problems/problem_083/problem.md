# Problem

## Problem Description

Assume that the causal impulse response \( g\left( t\right) \) is such that the transfer-function \( G\left( s\right) \) is asymptotically stable and \( \parallel G{\parallel }_{2} \) is bounded. If

\[
u\left( t\right)  = {u}_{\sigma }\left( t\right)  = \frac{g\left( {\sigma  - t}\right) }{\parallel G{\parallel }_{2}},\;\tau  \in  \left\lbrack  {0,\sigma }\right\rbrack  ,
\]

show that

\[
\mathop{\lim }\limits_{{\sigma  \rightarrow  \infty }}{\begin{Vmatrix}{u}_{\sigma }\end{Vmatrix}}_{2}^{2} = \mathop{\lim }\limits_{{\sigma  \rightarrow  \infty }}{\int }_{{0}^{ - }}^{\infty }{u}_{\sigma }{\left( \tau \right) }^{2}{d\tau } = 1
\]

and

\[
\parallel y{\parallel }_{\infty } \geq  \mathop{\lim }\limits_{{t \rightarrow  \infty }}\left| {y\left( t\right) }\right|  = \parallel G{\parallel }_{2}\parallel u{\parallel }_{2},
\]

to conclude that the inequality (3.49) is tight.

\[\|y\|_\infty \leq \|G\|_2 \|u\|_2. \tag{3.49}\]


## Subproblems

1. Compute the squared $L_2$ norm $\|u_\sigma\|_2^2$ of the input signal.
2. Show that
   $$
   \lim_{\sigma \to \infty} \|u_\sigma\|_2^2 = 1.
   $$
3. Express the output $y_\sigma(t)$ in terms of $g(t)$ and $\|G\|_2$.
4. Show that
   $$
   \|y\|_\infty \ge \lim_{t \to \infty} |y(t)| = \|G\|_2 \|u\|_2.
   $$
5. Conclude that the inequality
   $$
   \|y\|_\infty \le \|G\|_2 \|u\|_2
   $$
   is tight.

---

## Additional Information

- The $L_2$ norm of the transfer function is defined as
  $$
  \|G\|_2^2 = \int_{0^-}^{\infty} g^2(t)\, dt.
  $$
- The impulse response is causal: $g(t) = 0$ for $t < 0$.
- You may use basic properties of convolution and norm definitions.

---

## Constraints

- All steps must be justified analytically.
- Limits must be evaluated explicitly.
- Do not assume boundedness unless derived.
- Clearly distinguish between finite $\sigma$ and the limit $\sigma \to \infty$.
