# Solution

To find the limit of the Laplace transform of the unit pulse function, we utilize the integral definition and the sampling property of narrowed pulses.

---

## Method

## Step 1: Definition of the Laplace Transform
The Laplace transform of the pulse function $p_{\epsilon}(t)$ is given by:
$$
\mathcal{L}\{p_{\epsilon}(t)\} = \int_{0^{-}}^{\infty} p_{\epsilon}(t) e^{-st} dt
$$
Substituting the definition of $p_{\epsilon}(t)$, which is non-zero only on $[0, \epsilon]$, we get:
$$
\mathcal{L}\{p_{\epsilon}(t)\} = \int_{0^{-}}^{\epsilon} \frac{1}{\epsilon} e^{-st} dt
$$

---

## Step 2: Relation to the Sampling Property
Recall that for any continuous and differentiable function $f(t)$, the following property holds:
$$
\lim_{\epsilon \rightarrow 0} \int_{0^{-}}^{\infty} f(t) p_{\epsilon}(t) dt = f(0)
$$
In this specific problem, we can identify $f(t)$ as the exponential kernel of the Laplace transform:
$$
f(t) = e^{-st}
$$
Since $e^{-st}$ is continuous and differentiable for all $t$, it satisfies the conditions for the sampling property.

---

## Step 3: Evaluating the Limit
Taking the limit of the Laplace transform as $\epsilon \to 0$:
$$
\lim_{\epsilon \rightarrow 0} \mathcal{L}\{p_{\epsilon}(t)\} = \lim_{\epsilon \rightarrow 0} \int_{0^{-}}^{\infty} e^{-st} p_{\epsilon}(t) dt
$$
Applying the sampling property where $f(t) = e^{-st}$:
$$
= f(0) = e^{-s \cdot 0}
$$
Since $e^0 = 1$, we have:
$$
\lim_{\epsilon \rightarrow 0} \mathcal{L}\{p_{\epsilon}(t)\} = 1
$$

---

## Teaching Points
1. **Definition of $\delta(t)$ in Frequency Domain**: This result proves that the Laplace transform of an ideal impulse (Dirac Delta function) is $1$. Since $\lim_{\epsilon \to 0} p_{\epsilon}(t) = \delta(t)$, then $\mathcal{L}\{\delta(t)\} = 1$.
2. **Sifting/Sampling Property Application**: This problem demonstrates a practical application of the sampling property derived in previous proofs, where the integral "picks out" the value of the integrand at $t=0$.
3. **Unity Gain**: In system theory, an impulse input with a Laplace transform of 1 means the system's output (Impulse Response) directly represents the system's transfer function in the Laplace domain.
4. **Interchange of Limit and Integral**: This derivation assumes the validity of taking the limit of the integral for the pulse kernel, which is a standard approach in engineering analysis for generalized functions.