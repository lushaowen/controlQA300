# Problem: Effect of On/Off Temperature Band on Water Heater Performance

## Problem Description

Repeat the on/off control analysis of the residential water heater from
Problem P2.54, but with a narrower temperature band for the controller.

The heater parameters are unchanged:
- Volume: \( 50\;\mathrm{gal} \approx 0.19\;\mathrm{m^3} \)
- Heating power: \( 40{,}000\;\mathrm{BTU/h} \approx 12\;\mathrm{kW} \)
- Thermal resistance: \( R = 0.27\;\mathrm{K/W} \)
- Ambient temperature: \( T_o = 25^\circ\mathrm{C} \)
- No water flow: \( w = 0 \)

The new controller setpoints are:
- Turn-on temperature:  
  \( \underline{T} = 129.2^\circ\mathrm{F} \approx 54^\circ\mathrm{C} \)
- Turn-off temperature:  
  \( \bar{T} = 132.8^\circ\mathrm{F} \approx 56^\circ\mathrm{C} \)

The heater is initially full of water slightly below \( \underline{T} \).

---

## Subproblems

1. Compute the heating time from \( \underline{T} \) to \( \bar{T} \).
2. Compute the cooling time from \( \bar{T} \) back to \( \underline{T} \).
3. Determine the average water temperature over one on/off cycle.
4. Compute the average power consumption.
5. Compare the results with those of P2.54.
6. Discuss the impact of the choice of \( \underline{T} \) and \( \bar{T} \) on controller performance.

---

## Additional Information

- Use the same lumped thermal model as in P2.54.
- The heater operates at full power when on.
- Heat losses are linear and characterized by \( R \).

---

## Constraints

- Use SI units.
- Neglect flow effects and nonlinear heat transfer.
- Switching i
