---
layout: page
permalink: /projects/
title: research
description: Phase change in confined and complex multiphase systems — films, bubbles, drops, emulsions and porous media — at the crossroads of soft matter, interfacial hydrodynamics, capillarity and heat and mass transfer.
nav: true
nav_order: 2
---

<style>
  .proj { display: flex; gap: 1.4rem; margin-bottom: 2.8rem; align-items: flex-start; }
  .proj .proj-img { flex: 0 0 38%; max-width: 38%; }
  .proj .proj-img img { width: 100%; border-radius: 6px; }
  .proj .proj-body h3 { margin-top: 0; margin-bottom: 0.2rem; }
  .proj .proj-body .lead { color: var(--global-text-color-light); font-style: italic; margin-bottom: 0.5rem; }
  .proj .refs { font-size: 0.84rem; color: var(--global-text-color-light); border-left: 3px solid var(--global-theme-color); padding-left: 0.8rem; margin-top: 0.6rem; }
  .section-head { margin-top: 2.5rem; margin-bottom: 1.4rem; padding-bottom: 0.3rem; border-bottom: 2px solid var(--global-theme-color); }
  @media (max-width: 700px) {
    .proj { flex-direction: column; }
    .proj .proj-img { max-width: 100%; flex-basis: auto; }
  }
</style>

<h2 class="section-head">Ongoing projects</h2>

<div class="proj">
  <div class="proj-img"><img src="{{ '/assets/img/proj_condensation.jpg' | relative_url }}" alt=""></div>
  <div class="proj-body" markdown="1">
### Nucleation & condensation in polymer mixtures
<p class="lead">Biomimetic models of cellular condensates.</p>

Classical nucleation theory has long resisted experimental validation, very likely because critical nuclei are nanometric — far below optical resolution — so that by the time droplets become visible, other mechanisms have already blurred the picture.
Phase-separating polymer solutions provide a versatile platform to study nucleation and condensation dynamics, as nucleation occurs at micrometer scales and becomes optically resolvable. It has been shown that biomolecular condensates, the membraneless organelles in cells, assemble via liquid–liquid phase separation. Interestingly, their growth is arrested at a finite size, challenging classical nucleation and growth theories, as well as conventional emulsion stability principles.
Using polyvinyl alcohol solutions that phase separate upon heating, we build model systems to study homogeneous nucleation and condensation dynamics. Experiments are performed in liquid compartments produced within a temperature-controlled microfluidic device. This platform enables the investigation of the physical parameters governing nucleation, growth, coarsening and the ultimate growth arrest observed in cells.

<p class="refs">Funded by an ANR JCJC grant (ANR-25-CE30-2819), with Mathilde Reyssat and Élie Raphaël (Gulliver, ESPCI). Alice Mougey's PhD. Related: <a href="/publications/">Collective effects in breath figures</a> (PRF 2025), <a href="/publications/">Soft condensation</a> (PRL 2025).</p>
  </div>
</div>

<div class="proj">
  <div class="proj-img"><img src="{{ '/assets/img/proj_bubbles_stab.jpg' | relative_url }}" alt=""></div>
  <div class="proj-body" markdown="1">
### Thermocapillary (de)stabilization of surface bubbles
<p class="lead">When a small temperature difference decides whether a film lives or dies.</p>

A bare liquid film should drain and burst within milliseconds, yet surface bubbles survive for seconds when a temperature gradient runs across them. We showed that evaporative cooling of a bubble's apex sets up upward Marangoni flows that oppose gravitational drainage and select the film thickness — a thermal alternative to surfactants, demonstrated for Leidenfrost chimneys and for bubbles on heated oil. The reverse also holds: heating the top of a viscous bubble by just one degree drives downward flows that trigger early rupture. This dual control has drawn the interest of Saint-Gobain, for whom bubbles in molten glass spoil the final material.

<p class="refs">With Wilfried Raffi (intern) and Martin Coux (SGR/SVI). Related: <a href="/publications/">Thermal Marangoni bubbles</a> (Soft Matter 2022).</p>
  </div>
</div>

<div class="proj">
  <div class="proj-img"><img src="{{ '/assets/img/proj_evaporation.jpg' | relative_url }}" alt=""></div>
  <div class="proj-body" markdown="1">
### How surface bubbles accelerate evaporation
<p class="lead">A bubble turns slow diffusion into a convective jet.</p>

Evaporation from a confined liquid usually follows a slow diffusive law, the interface receding as the square root of time. We found that a single air bubble at the surface of a volatile liquid can speed this up by up to an order of magnitude. Schlieren imaging shows why: thermocapillary flows along the bubble funnel the surrounding vapor and eject it as a centimeter-scale plume, short-circuiting the diffusive bottleneck. A scaling model linking plume flux to bubble size matches independent mass-loss measurements. The result speaks to sea-spray aerosol production and drying in porous media, and naturally raises the question of water.

<p class="refs">Xue Ma's PhD, with Axel Huerre and Matthieu Roché (MSC). The water case is the focus of Clémence Fléchelle's upcoming thesis.</p>
  </div>
</div>

<div class="proj">
  <div class="proj-img"><img src="{{ '/assets/img/proj_nonwetting.jpg' | relative_url }}" alt=""></div>
  <div class="proj-body" markdown="1">
### Non-wetting by heat and motion
<p class="lead">Two ways to repel a liquid, and what happens when you combine them.</p>

A drop can be kept from wetting a solid either by heating the surface past the Leidenfrost point or by moving it fast enough — both create a thin gas layer that prevents contact. We ask whether these strategies add up. Millimetric drops are launched onto a substrate held at temperature *T* with a tangential velocity *v*, and we measure the levitation threshold. It falls sharply with speed: from about 200°C at rest down to room temperature near 1.35 m/s, where drops levitate "cold." This hybrid regime is exactly what glass-wool manufacturing faces, where binder droplets meet hot moving fibers.

<p class="refs">Tristan Simon's CIFRE PhD with Saint-Gobain, with Martin Coux (SGR/SVI) and Laurence Talini (SVI). Related: <a href="/publications/">Aerodynamic repellency of impacting liquids</a> (PRF 2018).</p>
  </div>
</div>

<div class="proj">
  <div class="proj-img"><img src="{{ '/assets/img/proj_hydrogels.jpg' | relative_url }}" alt=""></div>
  <div class="proj-body" markdown="1">
### Drying of salted hydrogels: model soils for salt deserts
<p class="lead">Reproducing the polygons of a salt flat in a transparent gel.</p>

The polygonal crusts of salt deserts like Uyuni are thought to arise from evaporation coupled to solutal convection in the porous ground. To test this, we dry salted agar hydrogels — transparent, controllable analogues of porous soils — and watch the flows driven by salt accumulation, the onset of instability, and the spatial scales it selects. The goal is to connect evaporation, solute transport and crystallization to the emergence of organized patterns.

<p class="refs">Funded by an IdEx Émergence grant.</p>
  </div>
</div>

<h2 class="section-head">Previous projects</h2>

<div class="proj">
  <div class="proj-img"><img src="{{ '/assets/img/proj_leidenfrost.jpg' | relative_url }}" alt=""></div>
  <div class="proj-body" markdown="1">
### Spontaneous dynamics of Leidenfrost drops
<p class="lead">How a levitating drop moves, oscillates and steers itself.</p>

During my PhD, I studied some of the spontaneous dynamics of Leidenfrost drops, which levitate on a cushion of thei
