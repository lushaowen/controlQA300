# Problem

## Problem Description

The scheme in the diagram in Fig. 4.21 is used to control a time-invariant system with a time-delay
\( \tau \ge 0 \),
represented by the transfer-function
\( e^{-s\tau} G \).

Show that

\[
u = \widehat{K}(\bar{y} - y),
\]

where

\[
\widehat{K} = \frac{K}{1 + (1 - e^{-s\tau}) GK}.
\]

The controller \( \widehat{K} \) is known as a Smith predictor.
Rearrange the closed-loop diagram in Fig. 4.21 so as to reveal the controller \( \widehat{K} \).

![alt text](images/bo_d5cu3iv7aajc7381m5hg_2_321_1838_498_309_0.jpg)

*Figure 4.21 Diagram for P4.11.*

## Subproblems

1. Write the control input \( u \) directly from the block diagram.
2. Identify the delayed and delay-free plant components.
3. Rearrange the expression to isolate \( u \).
4. Derive the effective controller \( \widehat{K} \).
5. Interpret the structure of \( \widehat{K} \) as a Smith predictor.
6. Redraw the closed-loop system to explicitly expose \( \widehat{K} \).

## Additional Information

- The plant contains a pure time delay.
- The controller has access to a model of the plant.
- The Smith predictor compensates for delay in the feedback path.
- All signals are Laplace-domain representations.

## Constraints

- Assume exact knowledge of the plant model.
- Do not approximate the delay.
- Use algebraic block-diagram manipulation.
- Do not rely on time-domain arguments.
