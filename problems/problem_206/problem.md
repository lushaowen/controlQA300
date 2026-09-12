# Problem

## Problem Description
The rotating machine is connected to a piston that applies a periodic torque that can be approximated by $ {\tau }_{2}\left( t\right)  = h\cos \left( {\sigma t}\right) $, where the angular frequency $ \sigma $ is equal to the angular velocity $ {\omega }_{2} $. Show that the modified equation including this additional torque is given by

\[
\left( {{J}_{1}{r}_{2}^{2} + {J}_{2}{r}_{1}^{2}}\right) {\dot{\omega }}_{1} + \left( {{b}_{1}{r}_{2}^{2} + {b}_{2}{r}_{1}^{2}}\right) {\omega }_{1} = {r}_{2}\left( {{r}_{2}\tau  + {r}_{1}{\tau }_{2}}\right) ,\;{\omega }_{2} = \left( {{r}_{1}/{r}_{2}}\right) {\omega }_{1}.
\]

Use the root-locus method to design a dynamic feedback controller that uses $ \tau $ as control input and $ {\omega }_{2} $ as the measured output so that the closed-loop system is capable of asymptotically tracking a constant reference input $ {\overline{\omega }}_{2}\left( t\right)  = {\overline{\omega }}_{2} = {4\pi }, t \geq  0 $, and asymptotically rejecting the torque perturbation $ {\tau }_{2}\left( t\right)  = h\cos \left( {\sigma t}\right) $ when $ \sigma  = {\overline{\omega }}_{2} $.

## Subproblems
1. Derive the combined dynamic equation for the belt-coupled rotational system under external periodic torque $ \tau_2(t) $ using force and moment balance.
2. Express the overall plant transfer function from control input $ \tau $ to output $ \omega_2 $, and identify its order and poles.
3. Model the disturbance $ \tau_2(t) = h \cos(\sigma t) $ in the Laplace domain and determine the required structure of the controller to achieve asymptotic rejection.
4. Apply the internal model principle to construct a controller with poles at $ s = 0 $ and $ s = \pm j\eta $ (where $ \eta = \overline{\omega}_2 $).
5. Augment the controller with finite zeros to stabilize the closed-loop system and shape the root locus for stability.
6. Analyze whether the resulting controller ensures both reference tracking and disturbance rejection without instability or oscillation issues.

## Additional Information 
- The piston-induced torque varies sinusoidally at a frequency matching the operating speed of the machine — an example of **self-excited disturbance**.
- This creates a resonance risk if not actively compensated.
- To reject such a signal, the controller must include a model of the disturbance generator — i.e., dynamics generating $ \cos(\sigma t) $ — which corresponds to poles on the imaginary axis at $ \pm j\sigma $.
- A pure integrator handles DC (constant) signals; similarly, conjugate imaginary poles handle sinusoidal disturbances.
- Without stabilizing zeros, adding these poles may cause instability due to excessive phase lag.

## Constraints
- Do not use state observers or state-feedback methods; only classical frequency-domain (root-locus) techniques are allowed.
- All physical parameters remain consistent with those defined in P6.11.
- The controller must not cancel any unstable or poorly damped plant poles.
- Stability must be guaranteed for some range of gain $ K > 0 $ via root-locus analysis.
- Final controller should be proper and physically realizable.
