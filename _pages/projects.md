---
layout: page
permalink: /projects/
title: Research
description: Phase change in confined multiphase systems — films, bubbles, drops, emulsions and porous media — at the crossroads of soft matter, interfacial hydrodynamics, capillarity and heat and mass transfer.
nav: true
nav_order: 2
---

<style>
  .proj { display: flex; gap: 1.4rem; margin-bottom: 2.8rem; align-items: flex-start; }
  .proj:nth-child(even) { flex-direction: row-reverse; }
  .proj .proj-img { flex: 0 0 38%; max-width: 38%; }
  .proj .proj-img img { width: 100%; border-radius: 6px; }
  .proj .proj-body h3 { margin-top: 0; margin-bottom: 0.2rem; }
  .proj .proj-body .lead { color: var(--global-text-color-light); font-style: italic; margin-bottom: 0.5rem; }
  .proj .refs { font-size: 0.84rem; color: var(--global-text-color-light); border-left: 3px solid var(--global-theme-color); padding-left: 0.8rem; margin-top: 0.6rem; }
  .section-head { margin-top: 2.5rem; margin-bottom: 1.4rem; padding-bottom: 0.3rem; border-bottom: 2px solid var(--global-theme-color); }
  @media (max-width: 700px) {
    .proj, .proj:nth-child(even) { flex-direction: column; }
    .proj .proj-img, .proj .proj-img { max-width: 100%; flex-basis: auto; }
  }
</style>

<h2 class="section-head">Ongoing projects</h2>

<div class="proj">
  <div class="proj-img"><img src="{{ '/assets/img/proj_condensation.jpg' | relative_url }}" alt="Nucleation in polymer mixtures"></div>
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
  <div class="proj-img"><img src="{{ '/assets/img/proj_bubbles_stab.jpg' | relative_url }}" alt="Thermocapillary stabilization of bubbles"></div>
  <div class="proj-body" markdown="1">
### Thermocapillary (de)stabilization of surface bubbles
<p class="lead">When a small temperature difference decides whether a film lives or dies.</p>

A bare liquid film should drain and burst within milliseconds, yet surface bubbles survive for seconds when a temperature gradient runs across them. We showed that evaporative cooling of a bubble's apex sets up upward Marangoni flows that oppose gravitational drainage and select the film thickness — a thermal alternative to surfactants, demonstrated for Leidenfrost chimneys and for bubbles on heated oil. The reverse also holds: heating the top of a viscous bubble by just one degree drives downward flows that trigger early rupture. This dual control has drawn the interest of Saint-Gobain, for whom bubbles in molten glass spoil the final material.

<p class="refs">With Wilfried Raff (intern). Related: <a href="/publications/">Thermal Marangoni bubbles</a> (Soft Matter 2022).</p>
  </div>
</div>

<div class="proj">
  <div class="proj-img"><img src="{{ '/assets/img/proj_evaporation.jpg' | relative_url }}" alt="Bubbles accelerating evaporation"></div>
  <div class="proj-body" markdown="1">
### How surface bubbles accelerate evaporation
<p class="lead">A bubble turns slow diffusion into a convective jet.</p>

Evaporation from a confined liquid usually follows a slow diffusive law, the interface receding as the square root of time. We found that a single air bubble at the surface of a volatile liquid can speed this up by up to an order of magnitude. Schlieren imaging shows why: thermocapillary flows along the bubble funnel the surrounding vapor and eject it as a centimeter-scale plume, short-circuiting the diffusive bottleneck. A scaling model linking plume flux to bubble size matches independent mass-loss measurements. The result speaks to sea-spray aerosol production and drying in porous media, and naturally raises the question of water.

<p class="refs">Xue Ma's PhD, with Axel Huerre and Matthieu Roché (MSC). The water case is the focus of Clémence Fléchelle's upcoming thesis. Submitted, 2026.</p>
  </div>
</div>

<div class="proj">
  <div class="proj-img"><img src="{{ '/assets/img/proj_nonwetting.jpg' | relative_url }}" alt="Non-wetting by heat and motion"></div>
  <div class="proj-body" markdown="1">
### Non-wetting by heat and motion
<p class="lead">Two ways to repel a liquid, and what happens when you combine them.</p>

A drop can be kept from wetting a solid either by heating the surface past the Leidenfrost point or by moving it fast enough — both create a thin gas layer that prevents contact. We ask whether these strategies add up. Millimetric drops are launched onto a substrate held at temperature *T* with a tangential velocity *v*, and we measure the levitation threshold. It falls sharply with speed: from about 200 °C at rest down to room temperature near 1.35 m/s, where drops levitate "cold." This hybrid regime is exactly what glass-wool manufacturing faces, where binder droplets meet hot moving fibers.

<p class="refs">Tristan Simon's CIFRE PhD with Saint-Gobain, with Martin Coux and Laurence Talini (SVI). Related: <a href="/publications/">Aerodynamic repellency of impacting liquids</a> (PRF 2018).</p>
  </div>
</div>

<div class="proj">
  <div class="proj-img"><img src="{{ '/assets/img/proj_hydrogels.jpg' | relative_url }}" alt="Drying of salted hydrogels"></div>
  <div class="proj-body" markdown="1">
### Drying of salted hydrogels: model soils for salt deserts
<p class="lead">Reproducing the polygons of a salt flat in a transparent gel.</p>

The polygonal crusts of salt deserts like Uyuni are thought to arise from evaporation coupled to solutal convection in the porous ground. To test this, we dry salted agar hydrogels — transparent, controllable analogues of porous soils — and watch the flows driven by salt accumulation, the onset of instability, and the spatial scales it selects. The goal is to connect evaporation, solute transport and crystallization to the emergence of organized patterns.

<p class="refs">Funded by an IdEx Émergence grant, supporting a PhD student arriving in 2026.</p>
  </div>
</div>

<h2 class="section-head">Previous projects</h2>

<div class="proj">
  <div class="proj-img"><img src="{{ '/assets/img/proj_leidenfrost.jpg' | relative_url }}" alt="Leidenfrost drops"></div>
  <div class="proj-body" markdown="1">
### Spontaneous dynamics of Leidenfrost drops
<p class="lead">How a levitating drop moves, oscillates and steers itself.</p>

During my PhD, I studied some of the spontaneous dynamics of Leidenfrost drops, which levitate on a cushion of their own vapor and behave as nearly frictionless objects. Small drops, below the capillary length, set themselves into motion without any external force. We showed that Leidenfrost drops host very strong inner flows, whose symmetry breaks as evaporation proceeds. In quasi-spherical drops, this flow takes the form of an asymmetric rolling motion that reshapes the vapor cushion beneath, giving the levitation force a horizontal component that propels the drop. 
Larger puddles, flattened by gravity, can spontaneously adopt pulsating star shapes. We showed that these pulsations originate in vibrations of the vapor film, which transiently excite subharmonic surface waves through a Faraday-like instability. Then, for certain radii, these waves can lock onto the Rayleigh–Lamb modes of the drop, giving rise to the star-shape pulsations. Finally, on a substrate heated with a gradient, drops drift toward the cold, driven by an asymmetric erosion of their base — a thermophobic motion that could be exploited in the design of self-guiding or self-cooling devices, in contrast with textured surfaces.

<p class="refs"><a href="/publications/">Leidenfrost wheels</a> (Nat. Phys. 2018), <a href="/publications/">Self-excitation of Leidenfrost drops</a> (PNAS 2021), <a href="/publications/">Symmetry breaking in Leidenfrost flows</a> (PRF 2018), <a href="/publications/">Thermophobic Leidenfrost</a> (Soft Matter 2021). Milton Van Dyke Award, APS DFD.</p>
  </div>
</div>

<div class="proj">
  <div class="proj-img"><img src="{{ '/assets/img/proj_viscoelastic.jpg' | relative_url }}" alt="Viscoelastic capillary singularities"></div>
  <div class="proj-body" markdown="1">
### Capillary singularities in viscoelastic fluids
<p class="lead">How a trace of polymer reshapes coalescence and pinch-off.</p>

During my postdoc at Twente, I studied how liquid viscoelasticity affects classical capillary singularities such as pinch-off, coalescence and spreading. While the global dynamics of a coalescing bridge barely change with added polymer, its spatial structure does: the bridge becomes markedly more angular, and a new self-similar structure emerges that collapses the profiles onto a universal curve. Even in tiny amounts, polymers regularize these singularities by introducing new length and time scales into the flow.

<p class="refs"><a href="/publications/">When elasticity affects drop coalescence</a> (PRL 2022), <a href="/publications/">Rapid viscoelastic spreading</a> (PRF 2022). Viscoelastic drainage with Stefan Karpitschka (Göttingen).</p>
  </div>
</div>

<div class="proj">
  <div class="proj-img"><img src="{{ '/assets/img/proj_soft_condensation.jpg' | relative_url }}" alt="Condensation on soft gels"></div>
  <div class="proj-body" markdown="1">
### Condensation on soft substrates
<p class="lead">How the softness of a surface reshapes a breath figure.</p>

When water vapor condenses on a solid, it forms a breath figure — the fog on cold glasses. I asked what happens when the surface is a soft gel instead, deformable by the capillary pull of each droplet. Using PDMS gels spanning four orders of magnitude in elastic modulus, I found that softer substrates nucleate far more droplets, and that once a first generation has formed, almost no new droplets appear between them. This contradicts both classical nucleation theory and standard elastocapillarity, since nucleation occurs at scales far below the elastocapillary length. Working with Bruno Andreotti, we showed that the vapor depletion around growing droplets not only slows their growth but screens nucleation in their vicinity, setting the droplet density from the very first instants. A collaboration with Uwe Thiele (Münster) further captured this through a mesoscopic gradient-dynamics model. These breath figures stay remarkably monodisperse, even at long times, offering a route to control condensation patterns.

<p class="refs"><a href="/publications/">Collective effects in breath figures</a> (PRF 2025), <a href="/publications/">Soft condensation</a> (PRL 2025), <a href="/publications/">Condensation on soft substrates: a mesoscopic perspective</a> (Mater. Adv. 2026). Master's work of Jim Scheefhals.</p>
  </div>
</div>


<div class="proj">
  <div class="proj-img"><img src="{{ '/assets/img/proj_solidification.jpg' | relative_url }}" alt="Frozen bubbles"></div>
  <div class="proj-body" markdown="1">
### Solidification of gas-laden media
<p class="lead">From a single trapped bubble to freeze–thaw cycles in model soils.</p>

When a freezing front meets a bubble, the competition between front speed and capillarity selects the final shape — from smooth engulfment with a singular tip to a stratified fragmentation, echoing the bubble columns of frozen lakes. At a larger scale, we study how freeze–thaw cycles in CO₂-laden water trap and release gas, as a model for permafrost, a major reservoir of greenhouse gases under a warming climate.

<p class="refs">Internships of Aymane Legssyer and Anne-Lou Pinot (frozen bubbles, with Caroline Cohen and Axel Huerre) and Céline Chebieb (freeze–thaw, with Axel Huerre).</p>
  </div>
</div>

<h2 class="section-head">Side projects</h2>

<div class="proj">
  <div class="proj-img"><img src="{{ '/assets/img/proj_side.jpg' | relative_url }}" alt="Side projects"></div>
  <div class="proj-body" markdown="1">
### Exploratory work
<p class="lead">Curiosity-driven problems, often born from teaching or internships.</p>

Alongside my main themes, I pursue more exploratory questions. We showed that the *Cheerios* attraction between floating objects gains a new, strongly dissipative lubrication regime in very viscous baths. The *rainbow twirler* — a toy of elastic ribbons under rotation — turns out to be well described by an Elastica equation enriched with inertia. I also study the peeling of ribbons from soft sticky gels, where elastocapillarity controls fingering at the peeling front. Earlier, during a research internship, I showed that marine choanoflagellates navigate oxygen gradients by a run-and-tumble strategy with logarithmic sensitivity.

<p class="refs"><a href="/publications/">Aerotaxis in the closest relatives of animals</a> (eLife 2016). Cheerios (Martin Trébosc) and twirler (with E. Reyssat) in preparation; peeling work with Menno Cornelissen.</p>
  </div>
</div>
