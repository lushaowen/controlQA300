# Problem: Interchange of Limit and Integration for Pulse Functions

## Problem Description
In the study of pulse functions $p_{\epsilon}(\tau)$ (such as the rectangular or continuous pulses used to approximate the Dirac Delta function), a fundamental question arises regarding the order of operations. 

Specifically, consider the results from previous analyses (e.g., $\int p_{\epsilon}(\tau)d\tau = 1$). Can one generally switch the order of the limit as $\epsilon \to 0$ and the integration operator? That is, does the following equality hold in the sense of standard Riemann integration?
$$
\lim_{\epsilon \rightarrow 0} \int_{0^{-}}^{t} p_{\epsilon}(\tau) d\tau \stackrel{?}{=} \int_{0^{-}}^{t} \lim_{\epsilon \rightarrow 0} p_{\epsilon}(\tau) d\tau
$$

Assume for this discussion that $p_{\epsilon}(t)$ is a continuous pulse approximation (e.g., a triangular or bell-shaped pulse) that narrows as $\epsilon \to 0$.

## Subproblems
1. Evaluate the left-hand side (LHS) of the equation based on the property that $p_{\epsilon}(\tau)$ is a unit pulse.
2. Determine the pointwise limit of $p_{\epsilon}(\tau)$ as $\epsilon \to 0$ for all $\tau \neq 0$ and $\tau = 0$.
3. Evaluate the right-hand side (RHS) by integrating the pointwise limit found in Subproblem 2.
4. Discuss why the standard Riemann integration framework fails to provide an affirmative answer to this equality.

## Additional Information
- **Pointwise Limit**: For a standard pulse, $\lim_{\epsilon \to 0} p_{\epsilon}(\tau) = 0$ for all $\tau \neq 0$, while the value at $\tau=0$ tends to infinity.
- **Interchange Criteria**: In calculus, the interchange of limits and integrals usually requires uniform convergence or the existence of an integrable bounding function (Lebesgue's Dominated Convergence Theorem).
- **Distributions**: The Dirac Delta "function" $\delta(t)$ is formally defined as a distribution or measure rather than a classical function.

## Constraints
- Analyze the problem using the concepts of boundedness and convergence.
- Contrast the results of classical Riemann integration with more advanced frameworks like Lebesgue integration or Distribution Theory.
- Explain the physical implication of this mathematical discrepancy.