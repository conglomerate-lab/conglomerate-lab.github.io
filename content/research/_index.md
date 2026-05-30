---
title: "Research"
layout: "simple"
---

<p style="font-size: 1.2rem; line-height: 1.6;">
The projects below reflect our current research efforts to advance understanding of granular and multiphase systems under various conditions.
<p>

<hr class="section-divider">

<div id="unsat-cpt" class="research-card top"> <!-- use top, right, or left for the figure-->
  
  <h2>Grain- and Pore-Scale Mechanics of Cone Penetration in Granular Soils</h2>
  
  <div class="research-content">
    <figure>
      <video autoplay muted loop playsinline>
        <source src="/videos/cpt_ver3.mp4" type="video/mp4">
      </video>
      <figcaption>
        Coupled LBM-DEM simulation of cone penetration in a saturated granular soil.
      </figcaption>
    </figure>
    <div>
      <p>The cone penetration test (CPT) is one of the most widely used tools for in situ characterization of soils, providing continuous measurements of penetration resistance that are used to infer geotechnical soil properties. However, CPT interpretation becomes significantly less reliable under non-standard conditions such as partial drainage or partial saturation, where existing correlations break down and the assumptions underlying conventional interpretation no longer hold. This project uses coupled lattice Boltzmann method and discrete element method (LBM-DEM) simulations to model CPT at the pore scale, directly resolving the interaction between grain motion and pore fluid during penetration. The goal is to build a mechanistic understanding of how drainage conditions and fluid phases influence penetration resistance and pore pressure response, with implications for more reliable CPT interpretation in complex field conditions.</p>
      Sponsor: Virginia Tech
    </div>
  </div>
</div>

<hr class="section-divider">

<div id="effective-stress" class="research-card top">

  <h2>Micromechanical Behavior of Unsaturated Granular Soils</h2>

  <div class="research-content">
    <figure>
      <video autoplay muted loop playsinline>
        <source src="/videos/drainage_comparison.mp4" type="video/mp4">
      </video>
      <figcaption>
      Comparison of drainage in a 2D porous medium as predicted by different LBM multifluid approaches (multiphase Shan–Chen, multicomponent Shan–Chen, and He–Chen–Zhang) and a physical model.
      </figcaption>
    </figure>
    <div>
      <p>Most soils in nature exist in an unsaturated state, with both water and air occupying the pore space between grains. The distribution of these fluid phases within the pore space gives rise to capillary forces between grains that affect soil stiffness and shear strength in ways that current engineering models capture only empirically, without a full mechanistic understanding of the underlying pore-scale physics. This project uses coupled multiphase LBM-DEM simulations to directly visualize and quantify how fluid distributions and capillary forces evolve at the grain scale under varying saturation conditions. Resolving the full three-phase interaction between water, air, and soil grains enables systematic investigation of how pore-scale processes influence the mechanical and hydraulic response of unsaturated soils, which can ultimately inform more reliable constitutive models for engineering practice.</p>
      Sponsor: German Research Foundation (DFG)
    </div>
  </div>
</div>

<hr class="section-divider">

<div id="frozen-soils" class="research-card right">

  <h2>Pore-Scale Freezing Mechanisms in Saturated and Unsaturated Soils</h2>

  <div class="research-content">
    <figure>
      <img src="/images/research/thermal_3d.gif" alt="Multiphase flow">
          <figcaption>
      LBM simulation of top-down freezing of an unsaturated soil sample.
      </figcaption>
    </figure>
    <div>
      <p>Frozen ground covers more than half of the Earth's land surface, and its mechanical behavior governs the performance of infrastructure in cold regions, from roads and pipelines to military installations in arctic environments. The thermo-hydro-mechanical behavior of freezing soils is fundamentally controlled by pore-scale processes: the distribution of ice, water, and air within the pore space, and how that distribution evolves as temperature drops. These processes are difficult to observe experimentally, leaving key mechanisms such as ice nucleation, cryogenic suction, and phase redistribution in unsaturated soils poorly understood. This project develops a pore-scale numerical framework coupling thermal LBM with multiphase LBM to simulate freezing in both saturated and unsaturated granular soils. By directly resolving phase evolution within complex pore geometries, the goal is to uncover the grain-scale mechanisms that govern frozen soil behavior and provide a foundation for more reliable predictive models in cold-region geotechnical engineering.</p>
      Sponsor: Cold Regions Research and Engineering Laboratory (ERDC-CRREL)
    </div>
  </div>
</div>
