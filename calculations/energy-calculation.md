# Preliminary energy calculation

## Purpose
Estimate the order of magnitude of the daily energy required to pump a reported 50 m³/day. This is an illustrative calculation only.

## Assumptions (not yet verified)
| Parameter | Assumed value |
|---|---:|
| Daily volume, V | 50 m³/day |
| Total dynamic head, H | 30 m |
| Overall efficiency, η | 0.60 (60%) |
| Pumping duration | 6 h/day |
| Water density, ρ | 1,000 kg/m³ |
| Gravitational acceleration, g | 9.81 m/s² |

## 1. Average flow during pumping
Q = 50 m³ ÷ 6 h = **8.33 m³/h**.

## 2. Daily energy estimate
Using:

E = (ρ × g × V × H) ÷ η

E = (1,000 × 9.81 × 50 × 30) ÷ 0.60 joules

Converting joules to kWh (1 kWh = 3.6 million joules):

E ≈ **6.81 kWh/day**.

## 3. Average electrical power while pumping
P = 6.81 kWh ÷ 6 h = **1.14 kW** (approximately).

## Interpretation and limitations
- These results depend on the assumed 30 m head and 60% overall efficiency.
- The actual total dynamic head must include the relevant elevation difference and hydraulic losses.
- The actual pump operating point must be checked against the manufacturer's pump curve.
- This energy estimate does not prove that a 15 kWp PV array will deliver the required energy in real operating conditions. Solar irradiation, temperature, orientation, shading, controller losses, operating schedule and seasonal conditions must also be assessed.
- Do not use this estimate as a final pump or PV-system sizing.

## Next calculation
Replace each assumption with measured or manufacturer-confirmed values, then compare predicted performance with daily operating records.
