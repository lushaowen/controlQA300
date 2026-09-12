# Problem

## Problem Description

Students participating in Rice University's Galileo Project [Jen14] set out to carefully reproduce some of Galileo's classic experiments. One was the study of projectile motion using an inclined plane, in which a ball accelerates down a plane inclined at a certain angle then rolls in the horizontal direction with uniform motion for a short while until falling off the edge of a table, as shown in Fig. 1.16. The distance the ball rolled along the inclined plane, $\ell$ in feet,and the distance from the end of the table to the landing site of the ball, $d$ in inches,were recorded. Some of their data,five trials at two different angles, is reproduced in Table 1.2. Use MATLAB to plot and visualize the data. Fit simple equations, e.g. linear, quadratic, etc., to the data to relate the fall height, $h$ ,to the horizontal travel distance, $d$ ,given in Table 1.2. Justify your choice of equations and comment on the quality of the fit obtained in each case. Estimate using the given data the vertical distance $y$ . Can you also estimate gravity?


![](images\image.png)

Figure 1.16 Galileo's inclined plane.


Table 1.2 Data for P1.10

| Try | Ramp distance at 13.4° |       |       |       |
|-----|------------------------|-------|-------|-------|
|     | 1 ft                   | 2 ft  | 4 ft  | 6 ft  |
| 1   | $13\frac{15}{16}$      | $19\frac{13}{16}$ | $27\frac{11}{16}$ | $33\frac{3}{8}$ |
| 2   | $13\frac{7}{8}$        | $19\frac{13}{16}$ | $27\frac{3}{4}$   | $33\frac{5}{16}$ |
| 3   | $14\frac{1}{16}$       | $19\frac{13}{16}$ | $27\frac{3}{4}$   | $33\frac{3}{16}$ |
| 4   | $14$                   | $19\frac{3}{4}$   | $27\frac{9}{16}$  | $33\frac{7}{16}$ |
| 5   | $13\frac{15}{16}$      | $19\frac{3}{4}$   | $27\frac{1}{16}$  | $33\frac{5}{8}$ |


Ramp distance at ${6.7}^{ \circ  }$

| Try | Ramp distance at 6.7° |       |       |       |       |
|-----|------------------------|-------|-------|-------|-------|
|     | 1 ft                   | 2 ft  | 4 ft  | 6 ft  | 8 ft  |
| 1   | $10\frac{1}{6}$        | $14\frac{1}{2}$   | $20\frac{3}{4}$   | $25\frac{7}{16}$  | $29\frac{5}{8}$  |
| 2   | $10\frac{1}{6}$        | $14\frac{9}{16}$  | $20\frac{3}{4}$   | $25\frac{1}{2}$   | $29\frac{1}{2}$  |
| 3   | $10\frac{1}{6}$        | $14\frac{1}{2}$   | $20\frac{3}{4}$   | $25\frac{3}{4}$   | $29\frac{1}{2}$  |
| 4   | $10\frac{1}{6}$        | $14\frac{1}{2}$   | $20\frac{3}{4}$   | $25\frac{1}{2}$   | $29\frac{5}{16}$ |
| 5   | $10\frac{11}{16}$      | $14\frac{9}{16}$  | $20\frac{3}{16}$  | $25\frac{5}{8}$   | $29\frac{1}{2}$  |



## Subproblems
1. Identify the structure of each block-diagram (series, parallel, or feedback).
2. Reduce each diagram step by step using block-diagram algebra.
3. Compute the overall transfer function from input $u$ to output $y$ for each case.
4. Clearly state any assumptions used in the derivation.

## Additional Information
- All blocks represent linear systems in the Laplace domain.
- Use standard block-diagram reduction rules.
- Feedback is assumed to be negative unless otherwise specified.

## Constraints
- All derivations must be shown.
- Express final answers in terms of the given block transfer functions.
- Use algebraic manipulation only (no numerical substitution).

