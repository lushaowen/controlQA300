# Problem: Modeling and Stability Analysis of a Falling Object with Air Resistance

## Problem Description
Consider the motion of an object of mass $m$ dropping vertically under the influence of constant gravitational acceleration $g$ and linear air resistance. The simplified ordinary differential equation (ODE) describing the velocity $v(t)$ is:
$$m\dot{v} + bv = mg$$
where $b > 0$ is the coefficient of air resistance and $m > 0$ is the mass.

Using the Laplace transform method, perform the following tasks:
1. Solve the differential equation for $v(t)$ assuming zero initial conditions.
2. Define the gravitational force $u(t) = mg$ as the system input. Calculate the transfer function $G(s) = \frac{V(s)}{U(s)}$ from the input force to the velocity.
3. Determine the transfer function $H(s) = \frac{X(s)}{U(s)}$ from the input force to the object's position $x(t)$, where $x(t) = \int_{0}^{t} v(\tau) d\tau$.
4. Evaluate whether these transfer functions are asymptotically stable.

## Subproblems
1. Apply the Laplace transform to the ODE to find $V(s)$.
2. Perform partial fraction expansion to find the time-domain solution $v(t)$.
3. Derive the transfer functions $G(s)$ (Velocity) and $H(s)$ (Position).
4. Analyze the poles of $G(s)$ and $H(s)$ to determine asymptotic stability.

## Additional Information
- The Laplace transform of a derivative is $\mathcal{L}\{\dot{f}(t)\} = sF(s) - f(0)$.
- The integration property of Laplace transform states $\mathcal{L}\{\int_{0}^{t} f(\tau) d\tau\} = \frac{F(s)}{s}$.
- A system is asymptotically stable if all poles of its transfer function have strictly negative real parts.

## Constraints
- Assume all physical constants ($m, b, g$) are positive.
- Assume zero initial conditions ($v(0) = 0, x(0) = 0$).
- Clearly show the partial fraction expansion steps.