# Problem: Solving Linear Ordinary Differential Equations Using Laplace Transforms

## Problem Description

Use the Laplace transform method to solve the following linear ordinary differential
equations (ODEs) subject to the given initial conditions.

Each problem involves either a first-order or second-order linear ODE with constant
coefficients, possibly including forcing functions such as constants, exponentials,
or trigonometric inputs.

You are required to apply the Laplace transform systematically, incorporate the
initial conditions in the Laplace domain, and compute the inverse Laplace transform
to obtain the solution in the time domain.

---

## Subproblems

### First-Order Differential Equations

**(a)**
\[
\dot{y} + y = 0, \quad y(0) = 1
\]

**(b)**
\[
\dot{y} + y = 1, \quad y(0) = 0
\]

**(c)**
\[
\dot{y} - y = 0, \quad y(0) = 1
\]

**(d)**
\[
\dot{y} - y = 1, \quad y(0) = 0
\]

---

### Second-Order Differential Equations (Homogeneous)

**(e)**
\[
\ddot{y} + \dot{y} = 0, \quad y(0) = 1,\; \dot{y}(0) = -1
\]

**(g)**
\[
\ddot{y} + y = 0, \quad y(0) = 1,\; \dot{y}(0) = -1
\]

**(l)**
\[
\ddot{y} + 2\dot{y} + y = 0, \quad y(0) = 1,\; \dot{y}(0) = 0
\]

**(n)**
\[
\ddot{y} + 2\dot{y} + 2y = 0, \quad y(0) = 1,\; \dot{y}(0) = 0
\]

---

### Second-Order Differential Equations (Forced)

**(f)**
\[
\ddot{y} + \dot{y} = e^{-t}, \quad y(0) = 0,\; \dot{y}(0) = 0
\]

**(h)**
\[
\ddot{y} + y = \cos(t), \quad y(0) = 0,\; \dot{y}(0) = 0
\]

**(i)**
\[
\ddot{y} + y = \cos(2t), \quad y(0) = 0,\; \dot{y}(0) = 0
\]

**(j)**
\[
\ddot{y} + y = \cos(t), \quad y(0) = 1,\; \dot{y}(0) = 0
\]

**(k)**
\[
\ddot{y} + y = \cos(2t), \quad y(0) = 1,\; \dot{y}(0) = 0
\]

**(m)**
\[
\ddot{y} + 2\dot{y} + y = \sin(t), \quad y(0) = \dot{y}(0) = 0
\]

**(o)**
\[
\ddot{y} + 2\dot{y} + 2y = \cos(t), \quad y(0) = \dot{y}(0) = 0
\]

---

## Additional Information

- All Laplace transforms are assumed to be one-sided
- Initial conditions are incorporated using standard Laplace properties:
  \[
  \mathcal{L}\{\dot{y}\} = sY(s) - y(0), \quad
  \mathcal{L}\{\ddot{y}\} = s^2Y(s) - sy(0) - \dot{y}(0)
  \]
- Use standard Laplace transform pairs for exponential and trigonometric functions

---

## Constraints

- All steps must be carried out using the Laplace transform method
- Initial conditions must be explicitly included in the Laplace domain
- Final answers must be exp
