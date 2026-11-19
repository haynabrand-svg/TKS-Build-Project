# TKS Build Project

[🇫🇷 Français](README.md) | [🇬🇧 English](README.en.md)

## Preliminary technical study — solar-powered water pumping in Senegal

### 1. Project objective
This project examines the general operation and preliminary energy requirements of a solar-powered water-pumping installation reportedly located in Notto, Senegal. The aim is to organize the available information, make a transparent first-order estimate, and identify the technical data needed before drawing conclusions about performance.

### 2. Information currently available

| Item | Reported value | Status |
|---|---:|---|
| Location | Notto, Senegal | Exact location to be confirmed |
| PV array capacity | 15 kWp | Reported; technical documentation not yet obtained |
| Water output | 50 m³/day | Reported; measured records not yet obtained |
| Pump type and model | Unknown | To be requested |
| Total dynamic head (TDH) | Unknown | To be measured/calculated |

These figures are preliminary inputs and are not independently verified measurements.

### 3. How the system works
Solar modules generate DC electricity. A suitable controller or variable-speed drive manages the electrical supply to the pump. The pump moves water through the pipework to a storage tank, from which it can be distributed. The exact electrical configuration and any storage or backup equipment remain to be confirmed.

See the [system flow diagram](diagrams/system-flow.en.md).

### 4. Preliminary hydraulic and energy estimate
A simplified estimate is provided using the following explicitly hypothetical assumptions:
- Daily water volume: 50 m³/day
- Total dynamic head: 30 m
- Overall pump-system efficiency: 60%
- Pumping duration: 6 hours/day

Under these assumptions:
- Required average flow during pumping: approximately 8.33 m³/h
- Estimated energy: approximately 6.81 kWh/day
- Average electrical power during the 6-hour pumping period: approximately 1.14 kW

**This is an illustrative estimate, not a validation of the installation or a final equipment sizing.** Actual energy requirements depend on measured water levels, total dynamic head, pipe losses, pump performance and operating conditions. See the [calculation details](calculations/energy-calculation.en.md).

### 5. Key information still needed
The main missing data are:
- Borehole depth and static/dynamic water levels
- Total dynamic head, including elevation and pipe losses
- Pump manufacturer, model, rated power and pump curve
- Controller / variable-speed drive model and configuration
- Actual flow rate and daily operating hours
- Tank capacity
- Measured daily water volumes and seasonal variation
- PV array configuration and measured production profile

See the [missing-data checklist](research/missing-data.en.md).

### 6. Provisional conclusion
The reported figures (15 kWp PV capacity and 50 m³/day water output) are not enough to establish whether the installation is correctly sized or to assess its efficiency. A reliable assessment requires the hydraulic operating point, pump curve, controller specifications and actual production data. The estimate in this repository is only a transparent starting point.

### 7. Project status
**Version:** V1 — preliminary analysis  
**Next step:** obtain technical specifications and operating measurements from the operator, then revise the calculations using confirmed data.

---
*This document is an independent preliminary study. Reported installation data should be confirmed with the operator before being treated as verified facts.*
