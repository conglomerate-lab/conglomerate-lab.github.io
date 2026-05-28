---
title: "Research"
layout: "simple"
---

Our research investigates the fundamental behavior of granular and multiphase fluid systems through grain-scale and pore-scale numerical simulations. The projects below reflect our current efforts to advance understanding in areas where experimental observation is limited and existing models fall short.

<hr class="section-divider">

<div id="unsat-cpt" class="research-card full-media">
  <h2>Pore-Scale Mechanics of Cone Penetration in Unsaturated Mine Tailings</h2>
  <video autoplay muted loop playsinline>
    <source src="/videos/cpt.mp4" type="video/mp4">
  </video>
    <p>Tailings storage facilities (TSFs) retain billions of tonnes of mining waste worldwide, and their failure can be catastrophic. Recent collapses in Brazil and Canada have caused hundreds of fatalities and released massive volumes of toxic slurry into surrounding ecosystems. A critical challenge in TSF safety is accurate material characterization, for which the cone penetration test (CPT) is the most widely used tool. However, existing CPT interpretation methods assume full saturation, while tailings in practice are often partially saturated. This mismatch can lead to unconservative estimates of soil strength, where a deposit may appear stable under CPT but become vulnerable to liquefaction and collapse once flooded. This project uses coupled LBM-DEM simulations to model CPT at the pore scale, directly resolving the interplay between drainage, fluid phases, and grain motion during penetration. The goal is to build a mechanistic understanding of how saturation state affects CPT resistance, ultimately improving the reliability of tailings characterization and reducing the risk of catastrophic failure.</p>
</div>

<hr class="section-divider">

<div id="effective-stress" class="research-card reverse">
  <figure>
    <img src="/images/research/scmp_drainage_sametime.gif" alt="LBM-DEM coupling">
    <figcaption>
    Simulation of drying of a 2D porous media
    </figcaption>
  </figure>
  <div>
    <h2>Grain-scale Origins of Effective Stress in Unsaturated Soils</h2>
    <p>Most soils in nature exist in an unsaturated state, with both water and air occupying the pore space between grains. The water menisci that form at air-water interfaces generate capillary forces between grains, forces that contribute to effective stress, stiffness, and shear strength in ways that are poorly captured by current engineering models. As a result, geotechnical design typically ignores unsaturated effects entirely, leading to overly conservative estimates that waste resources, or alternatively to dangerous miscalculations when saturation conditions change, as in rainfall-induced slope failures. This project uses coupled multiphase LBM-DEM simulations to directly visualize and quantify how capillary forces evolve at the grain scale under varying saturation conditions. By resolving the full three-phase interaction between water, air, and soil grains, the goal is to build a physics-based understanding of effective stress in unsaturated soils that can ultimately inform more reliable constitutive models for engineering practice.</p>
  </div>
</div>

<hr class="section-divider">

<div id="frozen-soils" class="research-card">
    <img src="/images/research/thermal_3d.gif" alt="Multiphase flow">
  <div>
    <h2>Pore-Scale Freezing Mechanisms in Saturated and Unsaturated Soils</h2>
    <p>Frozen ground covers more than half of the Earth's land surface, and its mechanical behavior governs the performance of infrastructure in cold regions, from roads and pipelines to military installations in arctic environments. The thermo-hydro-mechanical behavior of freezing soils is fundamentally controlled by pore-scale processes: the distribution of ice, water, and air within the pore space, and how that distribution evolves as temperature drops. These processes are difficult to observe experimentally, leaving key mechanisms such as ice nucleation, cryogenic suction, and phase redistribution in unsaturated soils poorly understood. This project develops a pore-scale numerical framework coupling thermal LBM with multiphase LBM to simulate freezing in both saturated and unsaturated granular soils. By directly resolving phase evolution within complex pore geometries, the goal is to uncover the grain-scale mechanisms that govern frozen soil behavior and provide a foundation for more reliable predictive models in cold-region geotechnical engineering.</p>
  </div>
</div>
