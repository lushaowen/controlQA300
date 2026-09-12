# Solution

## Method

Answers can vary widely depending on how students interpret the block-diagrams. Some possible simple answers for the first four blocks are:

a) inputs: motor voltage; outputs: motor speed; disturbances: none; open-loop; could be static (e.g. in steady-state) or dynamic (instantaneous); speed \( = K \times \) voltage.

b) inputs: motor voltage; outputs: motor acceleration; open-loop; dynamic; acceleration \( = K \times \) voltage.

c) inputs: hot, cold and position; This block-diagram shows an open-loop system with hot, cold and two position inputs as well as a water output. There are no disturbances. The two faucets could be modeled as static components.

d) This block-diagram shows a closed-loop system with reference temperature input and water (temperature) output. There are no disturbances. The thermostat compares the reference temperature with the actual water temperature and controls the heater. A simple model for the thermostat could be

\[
{e}_{h}\left( t\right)  = {t}_{r}\left( t\right)  - {t}_{w}\left( t\right)
\]

where \( {t}_{r} \) is the reference temperature, \( {t}_{w} \) the measured water temperature and \( {e}_{h} \) the temperature difference to be bridged by the heater. The heater could be modeled by a dynamic model that takes into account the time neeeded to heat the water.


## Teaching Points
1. Distinction between open-loop and closed-loop systems
2. Interpretation of physical signals in block-diagrams
3. Static vs dynamic system behavior
4. Role of feedback in control systems

