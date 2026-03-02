---
title: "Efecto de la viscosidad en la reflexión de ondas de choque cilíndricas sobre paredes rectas empleando OpenFOAM"
collection: publications
type: conference
permalink: /publication/conference/2023-11-06-mecom-efecto-viscosidad
date: 2023-11-06
venue: 'XXXIX Congress on Numerical Methods and their Applications - Argentina'
paperurl: 'https://amcaonline.org.ar/ojs/index.php/mc/article/view/6565'
---

*English title: Effect of viscosity on the reflection of cylindrical shock waves over straight walls using OpenFOAM*

### Project Overview
While many blast wave studies rely on inviscid (Euler) approximations, real-world applications involve viscous effects that can alter the shock structure. This paper presents a comparative study between inviscid and viscous (Navier-Stokes) models to determine how physical viscosity impacts the evolution of unsteady shock reflections.

**Key Highlights:**
* **Inviscid vs. Viscous Modeling:** Comparative analysis using the Euler equations against the Navier-Stokes equations to identify deviations in pressure peaks and shock positions.
* **OpenFOAM Implementation:** Use of the **rhoCentralFoam** solver, focusing on the resolution requirements to capture viscous scales ($y^+$) while maintaining stability with the KNP scheme.
* **Impact on Triple Point:** Numerical evidence showing that viscosity ($\mu$) influences the trajectory and the "roll-up" effect of the contact surface behind the triple point.


**Note:** This is a **peer-reviewed full paper** published in the congress proceedings.
