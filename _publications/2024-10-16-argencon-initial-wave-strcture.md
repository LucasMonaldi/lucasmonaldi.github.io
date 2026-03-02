---
title: "Estructura inicial de ondas en un blast tube"
collection: publications
type: conference
permalink: /publication/conference/2024-10-16-argencon-initial-wave-strcture
date: 2024-10-16
venue: 'IEEE Biennial Congress of Argentina (ARGENCON)'
paperurl: 'https://ieeexplore.ieee.org/document/10735984'
---

*English title: Initial wave structure in a blast tube after a sudden energy release*

### Project Overview
This research investigates the complex wave structure that follows a near-instantaneous energy release, leading to the configuration of a blast wave. The study focuses on understanding the one-dimensional ($1D$) evolution of the shock front, the contact surface, and the expansion fan in a blast tube environment.

**Key Highlights:**
* **Numerical Implementation:** High-fidelity simulations were performed using the **rhoCentralFoam** solver within **OpenFOAM**, employing the Kurganov-Noelle-Petrova (KNP) scheme.
* **Stability Analysis:** A detailed study on mesh sensitivity and the Courant-Friedrichs-Lewy ($CFL$) condition was conducted. A key finding was the necessity of using very low $CFL$ values to prevent spurious numerical oscillations during the early stages of energy release.
* **Thermodynamic Evolution:** The study tracks the temporal evolution of pressure, velocity, temperature, and density profiles, providing a clear picture of how the energy "bubble" transforms into a mature shock wave.
* **Scheme Comparison:** Evaluated the performance of first-order upwind vs. higher-order limiters, concluding that while stability is paramount, the KNP scheme effectively resolves the sharp gradients involved.

**Paper available**. Please contact me if you are interested: lucas.monaldi@unc.edu.ar

**Note:** This is a **peer-reviewed full paper** published in the congress proceedings.
