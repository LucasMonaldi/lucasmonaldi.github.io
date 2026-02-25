---
title: "OpenFOAM<sup>TM</sup> Simulation of the Shock Wave Reflection in Unsteady Flow"
collection: publications
type: journal
permalink: /publication/journal/2022-shock-reflection-openfoam
excerpt: 'A comprehensive validation of the KNP scheme in OpenFOAM for predicting regular and Mach shock reflections in unsteady flows.'
date: 2022-10-01
venue: 'Symmetry'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.mdpi.com/2073-8994/14/10/2048'
# bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
citation: 'Monaldi, L., Marcantoni, L. G., & Elaskar, S. (2022). OpenFOAM™ Simulation of the Shock Wave Reflection in Unsteady Flow. Symmetry, 14(10), 2048.'
---
### The challenge: Can CFD predict shock wave reflection over surfaces?

We are particularly interested in the reflection processes of an unsteady shock wave over a straight surface.

**What did we do?**
We simulated a shock wave traveling through a channel and hitting a wedge. This creates complex patterns: **Regular Reflection (RR)** and **Stochastic/Mach Reflection (MR)**. We compared the numerical results against the classic "Three-Shock Theory" to see if the software could really capture the physics.

**Key Findings:**
* **High Precision:** The solver accurately predicted the transition between reflection types, which is critical for the study of explosions or aerospace design.
* **Symmetry and Stability:** We confirmed that the numerical method maintains physical symmetry and handles the "triple point" (where three shock waves meet) without artificial oscillations.

**Why it matters:**
This paper serves as the **scientific backbone** that validates the tools I use in my current PhD research on blast loads and their interaction with solid surfaces.

![Shock Wave Reflection Patterns]({{ base_path }}/images/paper_symmetry_1.png)
*Figure: Wave structure obtained as numerical schlieren images. In this case we observed the incident shock, the reflected one, the Mach stem and the contact discontinuity.*

![Shock Wave Reflection Patterns Ben-Dor]({{ base_path }}/images/paper_symmetry_2.jpg)
*Figure:  Case of pseudo-steady transitional Mach-reflection. The position of the reflection point R, the triple point T and the second triple point T’ is shown. Adapted from Ben-Dor (2007).*
