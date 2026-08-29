# Closed-Wing Aircraft: Aerodynamic & Structural Analysis

A comparative study of a closed-wing aircraft configuration against a
conventional cantilever wing, combining CAD modelling, CFD analysis,
experimental aerodynamic validation, and structural analysis.

## Project Overview

Closed-wing configurations offer the potential for reduced induced drag,
improved structural stiffness, and more efficient load distribution by
eliminating conventional wing tips.

This project investigated the aerodynamic and structural characteristics
of a closed-wing configuration and compared its performance with a
conventional F16-type wing.

## Objectives

- Investigate the aerodynamic advantages of a closed-wing configuration.
- Compare aerodynamic performance with a conventional cantilever wing.
- Experimentally validate aerodynamic behaviour.
- Evaluate structural response under aerodynamic loading.

## Methodology

The study followed four major stages:

1. **Conceptual & CAD Development**
   - Developed 3D models of the conventional and closed-wing configurations.
   - Used the NACA 64A204 airfoil as the basis for the wing geometry.

2. **Computational Fluid Dynamics**
   - Conducted CFD simulations using ANSYS Fluent.
   - Compared both wing configurations across multiple angles of attack:
     `0°, 5°, 10°, 20°, 35°, 45°`
   - Evaluated aerodynamic quantities including lift and drag characteristics.

3. **Experimental Validation**
   - Conducted wind-tunnel testing to compare the aerodynamic behaviour
     of the conventional and closed-wing configurations.
   - Used a load-cell-based measurement system to obtain aerodynamic force data.
   - Investigated stall behaviour through flow-visualisation using threads.

4. **Structural Analysis**
   - Performed modal and linear-static FEA using ANSYS.
   - Evaluated natural frequencies, deformation, stresses and structural
     response under aerodynamic loading.

## Tools & Technologies

- **CFD:** ANSYS Fluent
- **Structural Analysis:** ANSYS
- **CAD:** Fusion 360
- **Experimental:** Open-blower wind tunnel, load cell, Arduino/ESP32
- **Post-processing:** Data plotting and comparison

## Key Findings

The study indicated improved aerodynamic and structural characteristics
for the investigated closed-wing configuration.

- **22.34% lower drag** than the conventional F16 wing at the same weight.
- **31.67% lower weight** for the same lift.
- CFD results were compared with experimental measurements to assess
  aerodynamic behaviour.

## Structural Analysis

The wing structure consisted of ribs, spars and a 3 mm aluminium-alloy skin.
Modal analysis identified multiple bending/torsional modes, while
linear-static analysis evaluated deformation and Von-Mises stress under
aerodynamic loading.

Representative results included:

- First bending mode: **33.01 Hz**
- Second bending mode: **114.59 Hz**
- Third bending mode: **250.31 Hz**
- Maximum deformation: **26.92 mm**
- Maximum Von-Mises stress: **724.74 MPa**

## Repository Contents

- `report/` — Detailed project report
- `figures/` — Selected CAD, CFD, experimental and structural figures
- `results/` — Selected numerical and experimental results

## Project Information

**Project:** Minor Project – B.Tech Aerospace Engineering  
**Institution:** Punjab Engineering College  
**Duration:** August–December 2023  
**Team:** Harsh Agarwal, Kartik Kumar  
**Faculty Incharge:** Prof. Tushar Siag
