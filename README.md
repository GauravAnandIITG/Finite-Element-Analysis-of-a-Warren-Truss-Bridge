# Finite Element Analysis of a Warren Truss Bridge

## Overview
This project presents a Finite Element Analysis (FEA) of a Warren Truss Bridge using ANSYS Mechanical. The study evaluates structural behavior under a uniformly distributed load, focusing on stress distribution, deformation, and internal forces.

---

## Authors
- Gaurav Anand (230104037)  
- Garv Roy Choudhary (230104036)  
- Gaurav Singh (230104039)  

Department of Civil Engineering  
Indian Institute of Technology Guwahati  

---

## Project Details

### Bridge Specifications
- Type: Warren Truss  
- Span Length: 8 m  
- Height: 2 m  
- Member Cross-section: 0.05 m × 0.05 m (square hollow section)  
- Deck: Shell element  

### Material Properties
- Material: Structural Steel  
- Young’s Modulus: 210 GPa  
- Poisson’s Ratio: 0.3  
- Density: 7850 kg/m³  

---

## Methodology

### Modeling
- Geometry created in ANSYS Mechanical  
- Truss members modeled as beam elements  
- Deck modeled as shell elements  

### Meshing
- Element size: ~0.35355 m  
- Growth rate: 1.2  
- Mesh quality: No errors  

### Boundary Conditions
- Left End: Displacement support  
- Right End: Fixed support  

### Loading
- Type: Surface pressure  
- Magnitude: 0.2 Pa  
- Direction: Normal to deck surface  

---

## Results

### Key Findings
- Maximum von-Mises Stress: 59.27 Pa  
- Maximum Deformation: 6.61 × 10⁻⁹ m  
- Maximum Direct Stress: ±137 Pa  
- Maximum Bending Moment: ~7.14 × 10⁻⁴ N·m  

### Observations
- Alternating tension and compression in diagonal members  
- Load transfer primarily through axial forces  
- Negligible deformation indicating high stiffness  
- Peak stresses observed near supports and loaded regions  

---

## Outputs Generated
- Axial Force Distribution  
- Direct Stress Contours  
- Equivalent (von-Mises) Stress  
- Bending Moment Diagrams  
- Shear Force Diagrams  
- Total Deformation Plot  

---

## Conclusion
The Warren truss bridge demonstrates efficient load distribution through axial forces with minimal bending. The stress and deformation values are negligible compared to the material yield strength (~250 MPa), indicating a structurally safe system under the applied load.

---

## Future Scope
- Apply realistic loads (kN/m² for vehicles and pedestrians)  
- Perform mesh convergence study  
- Evaluate reaction forces  
- Conduct dynamic and fatigue analysis  
- Study multiple load cases (asymmetric and point loads)  

---

## Tools Used
- ANSYS Mechanical (Static Structural Analysis)  

---

## Project Report
Refer to the full report for detailed analysis.
