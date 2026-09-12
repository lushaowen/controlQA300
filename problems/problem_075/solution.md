# Solution

The question of whether one can switch the limit and integration for pulse functions reveals the mathematical limitations of classical calculus when dealing with impulsive signals.

---

## Method

## Step 1: Evaluation of the Left-Hand Side (LHS)
From the definition of a unit pulse function $p_{\epsilon}(\tau)$, the area under the pulse is always maintained at unity regardless of $\epsilon$:
$$
\int_{0^{-}}^{t} p_{\epsilon}(\tau) d\tau = 1 \quad (\text{for } t > \epsilon)
$$
Taking the limit:
$$
\text{LHS} = \lim_{\epsilon \rightarrow 0} (1) = 1
$$

---

## Step 2: Evaluation of the Right-Hand Side (RHS)
Now we consider the pointwise limit of the function $p_{\epsilon}(\tau)$ inside the integral. 
- For any $\tau > 0$, as $\epsilon$ becomes smaller than $\tau$, $p_{\epsilon}(\tau)$ eventually becomes $0$. Thus, $\lim_{\epsilon \to 0} p_{\epsilon}(\tau) = 0$.
- For $\tau = 0$, $\lim_{\epsilon \to 0} p_{\epsilon}(0) = \infty$.
- For $\tau < 0$, $p_{\epsilon}(\tau) = 0$.

In the sense of classical functions, the pointwise limit is zero almost everywhere. Integrating this limit:
$$
\text{RHS} = \int_{0^{-}}^{t} (0) d\tau = 0
$$

---

## Step 3: Comparison and Theoretical Analysis
Since $1 \neq 0$, the order of limit and integration **cannot** be switched using standard Riemann integration. 

The mathematical reason is that $|p_{\epsilon}(t) - \lim_{\epsilon \to 0} p_{\epsilon}(t)|$ cannot be bounded by any fixed integrable function over an interval including the origin. As $\epsilon \to 0$, the height of the pulse tends to infinity, violating the requirements for uniform convergence and the conditions of the standard convergence theorems (like the Dominated Convergence Theorem) within the Riemann framework.

---

## Teaching Points
1. **Failure of Pointwise Limits**: This problem illustrates that the "limit of an integral" is not necessarily the "integral of the limit." This is a common pitfall in engineering mathematics.
2. **Necessity of Distributions**: To resolve this contradiction, mathematics employs **Distribution Theory** (or Generalized Functions). In this framework, $\delta(t)$ is not a function with values, but an operator defined by its effect under an integral.
3. **Riemann vs. Lebesgue**: While Riemann integration struggles with this singularity, Lebesgue integration and measure theory provide a more robust structure for handling such limits, although the Dirac Delta still requires treatment as a measure.
4. **Physical Insight**: Physically, an impulse represents a finite change (area=1) happening in zero time. The math confirms that we must focus on the *integrated effect* rather than the *instantaneous values* at the point of singularity.