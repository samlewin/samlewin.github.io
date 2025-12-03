---
layout: homepage
title: "Current Research"
permalink: /research
---

<style>
.image-text-container {
  display: flex;
  gap: 1rem;
  align-items: flex-start;
  width: 100%;
  flex-wrap: wrap; /* allow wrapping */
}

.image-text-container img {
  flex: 0 0 40%;
  max-width: 40%;
  height: auto;
  border-radius: 4px;
}

.image-text-container div {
  flex: 0 0 50%;
}

/* On narrow screens, stack items */
@media (max-width: 768px) {
  .image-text-container img,
  .image-text-container div {
    flex: 0 0 100%;
    max-width: 100%;
  }
}
</style>

## Ongoing Projects

<hr>

### Buoyancy-driven flows in coastal seas
<div class="image-text-container">
  <img src="./assets/img/GC_waves.png" alt="Inner shelf image">
  <div>
  In coastal seas, flows driven by horizontal heat and/or salinity differences interact with ambient stratification and shear, resulting in complex nonlinear dynamics. How can we characterise these processes and model the transport and mixing they facilitate?
  </div>
</div>
<br> 
_With [Jack McSweeney](https://jmcsweeney34.com/) (Stony Brook University)_
<hr>
### Internal wave-mean flow interactions
<div class="image-text-container">
  <img src="./assets/img/horizontalshear.jpeg" alt="Wave breaking">
  <div>
A significant portion of mechanical energy in the ocean is stored in and transported by internal gravity waves. How do these waves exchange energy and momentum with background currents, and how do these exchanges lead to instability and wave-breaking? 
  </div>
</div>
<br> 
_With [Miles Couchman](https://www.yorku.ca/professor/couchman/) (York University) and Arun Balakrishna (Stanford University)_
<hr> 
### Implicit large eddy simulation (ILES) for stratified interfacial flows
<div class="image-text-container">
  <img src="./assets/img/grav_current.png" alt="Gravity current">
<div>
ILES is a large eddy simulation approach for finite volume numerics in which dissipation is entirely numerical and provided by the chosen advection scheme (for example, a Weighted, Essentially Non-Oscillatory (WENO) scheme). How effectively does it capture properties of mixing in flows with sharp density and velocity interfaces, such as gravity currents?
</div>
</div>
<br>
_With Anant Ayyar (now CU Boulder)_
<hr> 

### Secondary shear instabilities in Kelvin-Helmholtz billows
<div class="image-text-container">
  <img src="./assets/img/secondaries.jpeg" alt="Secondary Instabilities">
<div>
Billow-like vortices produced by Kelvin-Helmholtz instability are commonly observed in the natural environment, though our ability to model the subsequent pathways to turbulence are restricted by the range of Reynolds numbers that are accessible computationally. What are the dynamics leading to the formation of secondary instabilities in the large Reynolds number limit?
</div>
</div>
<br> 
_With Emma Bouckley (University of Cambridge) and [Adrien Lefauve](https://www.alefauve.com/) (Imperial College London)_
