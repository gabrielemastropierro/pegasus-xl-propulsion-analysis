# Pegasus-XL Propulsion System Analysis and Design

Academic propulsion engineering project focused on the analysis and preliminary
sizing of the **Pegasus-XL launch vehicle propulsion system**.

The project was developed as part of the Aerospace Propulsion course during
the BSc in Aerospace Engineering at Politecnico di Milano.

The complete study covers the three solid-propellant stages of the Pegasus-XL
and the optional HAPS fourth stage, combining propulsion theory, engineering
models, MATLAB calculations and NASA CEA results.

---

## Project Overview

The objective of the project was to analyse the propulsion architecture of the
Pegasus-XL launch vehicle and reproduce the preliminary sizing and performance
evaluation of its propulsion stages.

The analysis considered:

- Mission profile
- Propellant characteristics
- Combustion properties
- Solid-propellant grain sizing
- Nozzle sizing
- Thrust and propulsion performance
- HAPS fourth-stage propulsion system
- Pressure losses
- Propellant tank sizing
- Injector-head analysis and sizing

The calculated results were compared with available reference data where
possible in order to assess the consistency and limitations of the engineering
models.

---

## Pegasus-XL Propulsion Architecture

The propulsion system considered in the project consists of four stages:

| Stage | Propulsion System |
|---|---|
| First Stage | Orion 50SXL |
| Second Stage | Orion 50XL |
| Third Stage | Orion 38 |
| Fourth Stage | HAPS |

The first three stages use solid rocket motors, while the HAPS stage provides
additional propulsion capability for the final orbital insertion phase.

---

## Mission Profile

The analysed mission profile considers the air launch of the Pegasus-XL from
its carrier aircraft.

The launch vehicle is released at approximately **11.9 km altitude** and
**Mach 0.82** before ignition of the first stage.

The subsequent propulsion sequence includes ignition and burnout of the three
main stages followed, when required, by operation of the HAPS fourth stage.

The mission profile was used to determine the operating conditions required
for the propulsion analysis.

---

# First Stage — Orion 50SXL

The first stage analysis included:

- Solid-propellant composition
- Combustion-property estimation
- NASA CEA analysis
- Propellant grain sizing
- Nozzle sizing
- Thrust calculation
- Performance evaluation

NASA CEA was used to estimate relevant combustion-gas properties from the
selected propellant composition and chamber conditions.

The nozzle was then sized using the estimated mass flow and thermodynamic
properties of the combustion products.

---

# Second Stage — Orion 50XL

A similar methodology was applied to the Orion 50XL second stage.

The analysis included:

- Reference motor data
- NASA CEA calculations
- Grain sizing
- Nozzle sizing
- Thrust evaluation
- Comparison with available reference performance

The different operating altitude and external pressure were considered during
the nozzle analysis.

---

# Third Stage — Orion 38

The third-stage study investigated the Orion 38 solid rocket motor.

The work included:

- Reference motor characteristics
- Propellant grain modelling
- Thrust-profile analysis
- Numerical integration of the thrust curve
- Nozzle sizing
- Performance calculations

The thrust profile was used to support the estimation of total impulse and
propellant requirements.

---

# Fourth Stage — HAPS

The **HAPS fourth stage** was analysed in greater detail as a small liquid
propulsion system used during the final part of the mission.

The study included:

- Propulsion-system architecture
- Engine operating conditions
- NASA CEA analysis
- Nozzle sizing
- Performance parameters
- Feed-system pressure losses
- Propellant tank sizing
- Injector-head research and preliminary sizing

This part of the project required combining propulsion theory with fluid
mechanics and preliminary component design.

---

## HAPS Nozzle Design

The nozzle sizing process used the combustion and operating conditions of the
HAPS engine to determine the principal geometric and performance parameters.

The analysis considered quantities such as:

- Chamber pressure
- Exhaust conditions
- Mass flow rate
- Throat area
- Exit area
- Expansion ratio
- Exhaust velocity
- Thrust

The resulting geometry was then used for the evaluation of the propulsion
performance.

---

## HAPS Performance Analysis

The main propulsion performance parameters were calculated from the engine
operating conditions and nozzle geometry.

The analysis included:

- Thrust
- Specific impulse
- Characteristic velocity
- Thrust coefficient
- Mass flow rate
- Exhaust velocity

These calculations provided a quantitative description of the expected HAPS
engine performance.

---

## Feed-System Pressure Losses

Pressure losses within the HAPS propellant feed system were analysed to
estimate the pressure required to guarantee the desired propellant flow.

The calculation considered the hydraulic behaviour of the feed line and the
pressure losses associated with the system.

This analysis connected the required combustion-chamber conditions with the
upstream propellant storage and feed system.

---

## Injector Head

The injector system was investigated as part of the preliminary design of the
HAPS propulsion system.

The work involved researching suitable injector concepts and performing a
preliminary sizing of the injector head based on the required engine operating
conditions.

The injector analysis was integrated with the feed-system and combustion
requirements to obtain a consistent preliminary propulsion-system design.

---

# My Contribution

This was a **group academic project**, with different parts of the propulsion
system analysed collaboratively by the team.

My main contribution focused on the **HAPS fourth stage**, particularly:

- Nozzle sizing
- Calculation and analysis of propulsion performance parameters
- Feed-system pressure-loss calculations
- Research into the injector-head configuration
- Preliminary injector-head sizing

This work required applying concepts from **rocket propulsion, compressible
flow and fluid mechanics** to the preliminary design and analysis of a real
aerospace propulsion system.

I also contributed to the integration and discussion of the fourth-stage
results within the complete Pegasus-XL propulsion analysis.

---

# Engineering Tools and Methods

The project involved the use of:

### MATLAB

MATLAB was used for numerical calculations and engineering analysis throughout
the propulsion-system study.

### NASA CEA

NASA **Chemical Equilibrium with Applications (CEA)** was used to determine
thermochemical properties of the combustion products required for subsequent
propulsion calculations.

### Engineering Models

Analytical and numerical engineering models were used for:

- Combustion analysis
- Grain sizing
- Nozzle design
- Compressible-flow calculations
- Propulsion performance
- Pressure-loss estimation
- Tank sizing
- Injector preliminary design

---

# What I Learned

The project provided practical experience in translating theoretical propulsion
concepts into a preliminary engineering design.

In particular, it strengthened my understanding of:

- Rocket propulsion fundamentals
- Nozzle design
- Compressible flow
- Propulsion performance parameters
- Feed-system analysis
- Pressure losses
- Injector design principles
- Numerical engineering calculations
- MATLAB-based analysis
- Interpretation of NASA CEA results
- Comparison between calculated and reference performance
- Collaborative engineering work

A particularly useful aspect of the project was understanding how individual
components cannot be analysed completely independently: nozzle performance,
mass flow, chamber conditions, feed-system pressure and injector design are
interconnected parts of the same propulsion system.

---

# Repository Structure

```text
pegasus-xl-propulsion-analysis/
│
├── README.md
│
├── report/
│   └── Pegasus_XL_Propulsion_Analysis.pdf
```

The repository contains the complete technical report and selected material
used to present the main engineering results.

---

# Technical Report

The complete methodology, calculations, assumptions and results are available
in the project report:

**`report/Pegasus_XL_Propulsion_Analysis.pdf`**

The report is presented as a **group project**, reflecting the collaborative
nature of the original academic work.

---

# Project Context

**Course:** Aerospace Propulsion  
**Degree:** BSc Aerospace Engineering  
**University:** Politecnico di Milano  
**Academic Year:** 2022–2023  
**Project Type:** Academic Group Project

---

# Author

**Group Project**

Personal contribution highlighted above.
