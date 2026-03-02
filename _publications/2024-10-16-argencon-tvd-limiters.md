---
title: "Influencia de limitadores TVD en la estructura de ondas producidas por la liberación de energía instantánea utilizando OpenFOAM"
collection: publications
type: conference
permalink: /publication/conference/2024-10-16-argencon-tvd-limiters.
date: 2024-10-16
venue: 'IEEE Biennial Congress of Argentina (ARGENCON)'
paperurl: 'https://ieeexplore.ieee.org/document/10735827'
---

*English title: Influence of TVD limiters on the wave structure produced by instantaneous energy release using OpenFOAM*

### Project Overview
Numerical simulations of blast waves require a delicate balance between high resolution and numerical stability. This study evaluates the influence of various Total Variation Diminishing ($TVD$) limiters—specifically **Minmod**, **van Leer**, and **van Albada**—on the formation and propagation of shock waves following a sudden energy release.

**Key Highlights:**
* **Numerical Schemes:** Comparative analysis between standard first-order upwind reconstruction and second-order schemes using different $TVD$ flux limiters.
* **Sensitivity Analysis:** Detailed investigation into the relationship between mesh resolution and the $CFL$ condition. A critical finding shows that implementing limiters requires an even stricter (lower) $CFL$ value than upwind schemes to properly describe the fluid field.
* **Wave Resolution:** The research demonstrates how different limiters affect the "sharpness" of the shock front, the contact surface, and the expansion fan, identifying which ones best minimize numerical diffusion without introducing oscillations.
* **OpenFOAM Framework:** All simulations were carried out using the **rhoCentralFoam** solver, providing a benchmark for high-speed compressible flow modeling.

**Paper available**. Please contact me if you are interested: lucas.monaldi@unc.edu.ar

**Note:** This is a **peer-reviewed full paper** published in the congress proceedings.
