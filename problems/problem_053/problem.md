# Problem: On/Off Control of a Residential Water Heater

## Problem Description

Most residential water heaters employ a simple on/off controller.
The heater turns on at full power when the water temperature \( T \) drops below a lower threshold \( \underline{T} \),
and turns off when the temperature reaches an upper threshold \( \bar{T} \).

Consider a 50-gallon water heater with:
- Volume: \( 50\;\mathrm{gal} \approx 0.19\;\mathrm{m^3} \)
- Heating power: \( 40{,}000\;\mathrm{BTU/h} \approx 12\;\mathrm{kW} \)
- Thermal resistance: \( R = 0.27\;\mathrm{K/W} \)
- Ambient temperature: \( T_o = 25^\circ\mathrm{C} \)
- No water inflow or outflow: \( w = 0 \)

The on/off controller is set as:
- Turn on at \( \underline{T} = 122^\circ\mathrm{F} \approx 50^\circ\mathrm{C} \)
- Turn off at \( \bar{T} = 140^\circ\mathrm{F} \approx 60^\circ\mathrm{C} \)

Assume the heater is initially full with water slightly below \( \underline{T} \).

---

## Subproblems

1. Formulate the temperature dynamics during the heating (on) phase.
2. Formulate the temperature dynamics during the cooling (off) phase.
3. Compute the duration of each phase in a complete on/off cycle.
4. Determine the average water temperature over one full cycle.
5. Compute the average power consumption.
6. Sketch or simulate the water temperature over a 24-hour period.

---

## Additional Information

- Use the lumped thermal model from P2.49.
- Assume constant heater power when on.
- The system alternates between two linear dynamics depending on temperature.

---

## Constraints

- Use SI units consistently.
- Assume perfect mixing.
- Neglect nonlinear heat-transfer effects.
