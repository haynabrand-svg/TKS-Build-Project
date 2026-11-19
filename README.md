# TKS Build Project
## Preliminary technical study — solar-powered water pumping in Senegal

### 1. Project objective
This project examines the basic operation and preliminary energy requirements of a solar-powered water-pumping installation reportedly located in Notto, Senegal. The aim is to organize the available information, make a transparent first-order estimate, and identify the technical data needed before drawing conclusions about performance.

### 2. Information currently available

| Item | Reported value | Status |
|---|---:|---|
| Location | Notto, Senegal | To confirm precisely |
| PV array capacity | 15 kWp | Reported; technical documentation not yet obtained |
| Water output | 50 m³/day | Reported; measured records not yet obtained |
| Pump type and model | Unknown | To request |
| Total dynamic head (HMT) | Unknown | To measure/calculate |

The figures above are preliminary project inputs, not independently verified measurements.

### 3. How the system works
Solar modules generate DC electricity. A suitable controller or variable-speed drive manages the electrical supply to the pump. The pump lifts water through the pipework to a storage tank, from which water can be distributed. The exact electrical configuration and any storage or backup equipment remain to be confirmed.

See [the system flow diagram](diagrams/system-flow.md).

### 4. Preliminary hydraulic and energy estimate
A simplified calculation is provided using explicitly hypothetical assumptions:
- Daily water volume: 50 m³/day
- Total dynamic head: 30 m
- Overall pump-system efficiency: 60%
- Pumping duration: 6 hours/day

Under these assumptions:
- Required average flow during pumping: approximately 8.33 m³/h
- Hydraulic/electrical energy estimate: approximately 6.81 kWh/day
- Average electrical power during the 6-hour pumping period: approximately 1.14 kW

**This is an illustrative estimate, not a system validation or final equipment sizing.** The actual energy requirement depends strongly on measured water levels, total dynamic head, pipe losses, pump performance and operating conditions. See [calculation details](calculations/energy-calculation.md).

### 5. Key information still needed
The most important missing data are:
- Borehole depth and static/dynamic water levels
- Total dynamic head, including elevation and pipe losses
- Pump manufacturer, model, rated power and pump curve
- Controller / variable-speed drive model and configuration
- Actual flow rate and daily operating hours
- Tank capacity
- Measured daily water volumes and seasonal variation
- PV array configuration and measured production profile

See the [missing-data checklist](research/missing-data.md).

### 6. Provisional conclusion
The reported figures (15 kWp PV capacity and 50 m³/day water output) are not enough on their own to establish whether the installation is correctly sized or how efficiently it operates. A reliable assessment requires the hydraulic operating point, pump curve, controller details and measured production data. The estimate in this repository is only a transparent starting point.

### 7. Project status
**Version:** V1 — preliminary analysis  
**Next step:** obtain technical specifications and operating measurements from the operator, then revise the calculations using confirmed data.

---
*This document is an independent preliminary study. Reported installation data should be confirmed with the operator before being treated as verified facts.*
