# Problem

## Problem Description

Explain why the controller in Fig. 4.21 can be used only if \( G \) is asymptotically stable.


## Subproblems

1. Identify the poles and zeros of the Smith predictor controller \( \widehat{K} \).
2. Analyze the interaction between \( \widehat{K} \) and the delayed plant \( e^{-s\tau}G \).
3. Determine the pole-zero cancellations occurring in the closed-loop system.
4. Explain the implications of these cancellations for internal stability.
5. Conclude why asymptotic stability of \( G \) is required.
![alt text](images/bo_d5cu3iv7aajc7381m5hg_2_321_1838_498_309_0.jpg)
Fig. 4.21 
## Additional Information

- The controller \( \widehat{K} \) is defined as
  \[
  \widehat{K} = \frac{K}{1 + (1 - e^{-s\tau}) GK}.
  \]
- The closed-loop structure corresponds to the Smith predictor configuration.
- Internal stability requires stability of all internal signals.

## Constraints

- Use frequency-domain and pole-zero arguments.
- Do not assume robustness to modeling errors.
- Internal stability must be explicitly addressed.
- The
