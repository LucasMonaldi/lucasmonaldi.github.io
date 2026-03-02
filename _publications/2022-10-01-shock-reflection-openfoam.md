---
title: "OpenFOAM<sup>TM</sup> Simulation of the Shock Wave Reflection in Unsteady Flow"
collection: publications
type: journal
permalink: /publication/journal/2022-10-01-shock-reflection-openfoam
excerpt: 'A comprehensive validation of the KNP scheme in OpenFOAM for predicting regular and Mach shock reflections in unsteady flows.'
date: 2022-10-01
venue: 'Symmetry'
paperurl: 'https://www.mdpi.com/2073-8994/14/10/2048'
citation: 'Monaldi, L., Marcantoni, L. G., & Elaskar, S. (2022). OpenFOAM™ Simulation of the Shock Wave Reflection in Unsteady Flow. Symmetry, 14(10), 2048.'
---
### The physics of shock wave reflections

One of the hardest things to simulate in high-speed aerodynamics is how shock waves reflect when they hit a surface. If the math is slightly off, the entire pressure distribution fails. In this paper, we put the **KNP scheme** (within the rhoCentralFoam solver) to the test.

**What did we do?**
We simulated a shock wave traveling through a channel and hitting a wedge. This creates complex patterns: **Regular Reflection (RR)** and **Stochastic/Mach Reflection (MR)**. We compared the numerical results against the classic "Three-Shock Theory" to see if the software could really capture the physics.

**Key Findings:**
* The solver accurately predicted the transition between reflection types, which is critical for aerospace design.
* We confirmed that the numerical method maintains physical symmetry and handles the "triple point" (where three shock waves meet) without artificial oscillations.

 **Why it matters:**

This paper serves as the **scientific backbone** that validates the tools I use in my current PhD research on blast loads and their interaction with solid surfaces.


![Shock Wave Reflection Patterns]({{ base_path }}/images/paper_symmetry_1.png)

*Figure: Wave structure obtained as numerical schlieren images. In this case we observed the incident shock, the reflected one, the Mach stem and the contact discontinuity.*


![Shock Wave Reflection Patterns Ben-Dor]({{ base_path }}/images/paper_symmetry_2.jpg)

*Figure:  Case of pseudo-steady transitional Mach-reflection. The position of the reflection point R, the triple point T and the second triple point T’ is shown. Adapted from Ben-Dor (2007).* 

**Paper available**. Please contact me if you are interested: [lucas.monaldi@unc.edu.ar](mailto:lucas.monaldi@unc.edu.ar)
