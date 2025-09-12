# Setup

| Category             | Configuration                       |
|---------------------|-------------------------------------|
| Models              | Energy, k-ε Turbulence, P1 Radiation |
| Species             | Non-Premixed Combustion             |
| Boundary Conditions |                                     |
| → Inlet             | Mass Flow                           |
| → Outlet            | Pressure Outlet                     |
| → Symmetry          | Yes                                 |
| → Wall              | Yes                                 |

## Boundary Conditions
The boundary conditions were derived from experimental data reported by G. Motta [1], and the airflow distribution was calculated proportionally to the inlet areas, adapted to the geometry developed in this work.

| Inlet              | Mass Flow [kg/s] | Initial Gauge Pressure [Pa] |
|--------------------|-----------------|-----------------------------|
| inlet_cooling_1    | 0.015           | 689000                      |
| inlet_cooling_2    | 0.00769         | 689000                      |
| inlet_combustion   | 0.497           | 689000                      |
| inlet_dil_1        | 0.3199          | 689000                      |
| inlet_dil_2        | 0.506           | 689000                      |
| inlet_fuel         | 0.0347          | 0                           |
| inlet_swirler      | 0.384           | 689000                      |

---

## References

[1] G. Motta, "CFD Simulation and Emissions Prediction from a Helicopter Engine," M.S. thesis, Dept. of Chemistry, Materials and Chemical Engineering "G. Natta," Politecnico di Milano, Milan, Italy, 2016. Supervisor: Prof. A. Frassoldati.

