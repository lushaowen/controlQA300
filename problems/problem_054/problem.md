# Problem: On/Off Control of a Water Heater with Constant In/Out Flow

## Problem Description

Repeat the analysis of the residential water heater with an on/off controller
, but now assume a constant inflow and outflow of water.

The heater parameters are:
- Volume: \( 50\;\mathrm{gal} \approx 0.19\;\mathrm{m^3} \)
- Heating power: \( 40{,}000\;\mathrm{BTU/h} \approx 12\;\mathrm{kW} \)
- Thermal resistance: \( R = 0.27\;\mathrm{K/W} \)
- Ambient and inlet temperature:  
  \( T_o = T_i = 25^\circ\mathrm{C} \)

The controller thresholds are:
- Turn on at \( \underline{T} = 50^\circ\mathrm{C} \)
- Turn off at \( \bar{T} = 60^\circ\mathrm{C} \)

A constant water inflow/outflow of:
\[
w = 20\;\mathrm{gal/h} \approx 21 \times 10^{-6}\;\mathrm{m^3/s}
\]
is present at ambient temperature.

---

## Subproblems

1. Derive the temperature dynamics during the heating (on) phase with flow.
2. Derive the temperature dynamics during the cooling (off) phase with flow.
3. Compute the duration of each phase in one complete on/off cycle.
4. Determine the average water temperature over one cycle.
5. Compute the average power consumption.
6. Compare the results with the no-flow case (P2.54).

---

## Additional Information

- Use the same lumped-parameter thermal model as in P2.54.
- Assume perfect mixing and constant flow.
- Power is either full on or completely off.

---

## Constraints

- Use SI units.
- Neglect nonlinear heat-transfer effects.
- The system switches instantaneously at the temperature thresholds.
