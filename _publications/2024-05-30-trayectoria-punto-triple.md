---
title: "Trayectoria del punto triple de una reflexión de onda de choque inestacionaria sobre pared recta"
collection: publications
type: journal
permalink: /publication/journal/2024-05-30-trayectoria-punto-triple
excerpt: 'A numerical study on the evolution of the triple point in unsteady Mach reflections, validated against experimental and theoretical data.'
date: 2024-05-30
venue: 'Revista Facultad de Ciencias Básicas'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://revistas.umng.edu.co/index.php/rfcb/article/view/7052'
# bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
citation: 'Monaldi, L., Matallana, G., Gutiérrez Marcantoni, L. F., & Elaskar, S. (2024). Trayectoria del punto triple de una reflexión de onda de choque inestacionaria sobre pared recta. Revista Facultad De Ciencias Básicas, 18(2), 63–70. https://doi.org/10.18359/rfcb.7052'
---

In this research, we focus on the **triple point**: the specific junction where three shock waves meet during an explosion. Understanding its trajectory is crucial because it defines the boundary of the most destructive pressure zones near the ground.

**What did we do?**
We simulated a sudden energy release generating a cylindrical shock wave. As this wave travels along a straight wall, the point where it meets the surface rises, forming what is known as the "Mach stem." Using **OpenFOAM<sup>TM</sup>**, we tracked this trajectory and compared it with classical pseudo-steady mathematical models and experimental data.

**Key Findings:**
* **Solver Precision:** The KNP scheme accurately captured the evolution of the unsteady process, showing high fidelity in the early stages of the reflection.
* **Physical Deviations:** We noted that as the wave progresses ($x > 3.5$ m), numerical results begin to deviate from simplified theories. This highlights why high-fidelity CFD is essential for real-world safety assessments where simple formulas might fall short.

**Why it matters:**
Predicting the triple point's height allows engineers to determine how high a structure must be to be hit by the maximum pressure zone of a blast. This paper completes my series of validations on shock wave physics.

![Triple Point Trajectory]({{ base_path }}/images/paper_trayectoria.jpg)
*Figure: Triple Point trajectory in Schlieren images. The incident and reflected shock waves, the Mach stem, and the contact discontinuity are also observed.*
