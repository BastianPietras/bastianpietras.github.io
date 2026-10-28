---
layout: page
title: projects
permalink: /projects/
description:
---

<style>
.projects-story { line-height: 1.65; }
.projects-story .research-intro { max-width: 48em; margin-bottom: 2.5rem; }
.projects-story h2 { line-height: 1.25; margin-top: 0; }
.projects-story .research-project { display: grid; grid-template-columns: minmax(0, 1fr) minmax(0, 2fr); gap: 2rem; padding: 2rem 0; border-top: 1px solid #ddd; }
.projects-story .research-project img { width: 100%; height: auto; display: block; }
.projects-story .research-question { font-weight: bold; }
.projects-story .research-links { padding-left: 1.2rem; margin-bottom: 0; }
.projects-story .research-links li { margin-bottom: .4rem; }
.projects-story .research-direction, .projects-story .research-contact { border-top: 1px solid #ddd; padding-top: 2rem; margin-top: 1rem; }
@media (max-width: 640px) {
  .projects-story .research-project { grid-template-columns: minmax(0, 1fr); gap: 1.25rem; }
  .projects-story .research-project img { max-width: 340px; margin: 0 auto; }
  .projects-story h2 { font-size: 1.5rem; }
}
</style>

<div class="projects-story">
<section class="research-intro" aria-labelledby="research-intro-title">
<h2 id="research-intro-title">From single neurons to collective dynamics</h2>
<p>How do cellular mechanisms give rise to the activity of neural populations? I use nonlinear dynamics, statistical physics and mean-field theory to build models that preserve the mechanisms that matter while remaining simple enough to understand and test.</p>
<p>The projects below connect exact mathematical reductions with synchronization, fluctuations and transient activity. Together, they form the basis for my emerging work on multiscale brain dynamics and the interactions among brain, body and environment.</p>
</section>
<section class="research-project" aria-labelledby="research-project-1">
<div><img src="{{ site.baseurl }}/assets/img/qifgap_cover1.png" alt="Schematic of chemical and electrical coupling in a neuronal network" loading="lazy"></div>
<div>
<h2 id="research-project-1">Exact reductions of spiking networks</h2>
<p class="research-question">Which cellular and synaptic mechanisms shape collective activity?</p>
<p>I develop low-dimensional descriptions of spiking-neuron populations that retain a direct connection to the underlying network. My work examines how chemical and electrical synapses, spike shape and adaptation alter synchronization and population dynamics. These models make it possible to analyse mechanisms that are difficult to isolate in large simulations.</p>
<ul class="research-links">
<li><a href="https://bastianpietras.github.io/projects/4QIFgap/">Project background</a></li>
<li><a href="https://doi.org/10.1103/PhysRevE.111.014422">Adaptation paper · 2025</a></li>
<li><a href="https://doi.org/10.1162/neco_a_01680">Spike-shape paper · 2024</a></li>
</ul>
</div>
</section>
<section class="research-project" aria-labelledby="research-project-2">
<div><img src="{{ site.baseurl }}/assets/img/stochring_cover.png" alt="Space-time view of simulated neuronal population activity" loading="lazy"></div>
<div>
<h2 id="research-project-2">Fluctuations, replay and metastability</h2>
<p class="research-question">How can transient activity emerge and move through a neural population?</p>
<p>Finite networks fluctuate, and those fluctuations can matter. With Valentin Schmutz and Tilo Schwalger, I developed a mesoscopic description of spiking networks with short-term plasticity to study hippocampal replay and metastability. This work connects microscopic spiking variability to transient population activity, rather than treating variability only as noise around an average.</p>
<ul class="research-links">
<li><a href="https://doi.org/10.1371/journal.pcbi.1010809">Replay paper · 2022</a></li>
<li><a href="https://www.youtube.com/watch?v=hLkP9h434fI">Related neural-field animation</a></li>
</ul>
</div>
</section>
<section class="research-project" aria-labelledby="research-project-3">
<div><img src="{{ site.baseurl }}/assets/img/lowdim_cover.png" alt="Comparison of population responses and reduced-model approximations" loading="lazy"></div>
<div>
<h2 id="research-project-3">Firing-rate models beyond the stationary state</h2>
<p class="research-question">How much of a population response can a small model preserve?</p>
<p>Using a spectral decomposition of the refractory-density equation, I derive reduced firing-rate models for renewal-type spiking neurons. The approach links single-neuron spike statistics to population time scales and captures synchronization and fast transient responses that simpler rate descriptions can miss.</p>
<ul class="research-links">
<li><a href="https://bastianpietras.github.io/projects/2spectral_decomp/">Project and figures</a></li>
</ul>
</div>
</section>
<section class="research-project" aria-labelledby="research-project-4">
<div><img src="{{ site.baseurl }}/assets/img/phd_cover2.png" alt="Illustration from the phase-synchronization research project" loading="lazy"></div>
<div>
<h2 id="research-project-4">Synchronization across interacting populations</h2>
<p class="research-question">When do interacting oscillators coordinate, and when do they split into distinct rhythms?</p>
<p>My work on phase reduction and coupled-oscillator networks provides a mathematical foundation for studying collective neural dynamics. I investigate how coupling and heterogeneity shape synchronization and transitions between collective states, connecting tractable oscillator descriptions to questions about interacting neuronal populations.</p>
<ul class="research-links">
<li><a href="https://research.vu.nl/en/publications/modeling-phase-synchronization-of-interacting-neuronal-population">Doctoral thesis</a></li>
<li><a href="https://bastianpietras.github.io/publications/">Publications and review articles</a></li>
</ul>
</div>
</section>
<section class="research-direction">
<h2>Looking ahead: brain, body and behaviour</h2>
<p>I am interested in extending mechanistic population models towards whole-brain dynamics and closed-loop interactions among brain, body and environment. A central question is which local circuit properties need to be preserved to explain differences in large-scale activity and behaviour.</p>
<p>This is an emerging research direction: I aim to combine interpretable models with neural, physiological and behavioural observations, using data to test which mechanisms matter across scales.</p>
</section>
<section class="research-contact">
<h2>Collaborations</h2>
<p>I welcome collaborations that connect mathematical models with experimental observations, especially across neuronal populations, brain rhythms and sensorimotor dynamics.</p>
<p><a href="mailto:bastian@nisys.ai">Contact me</a></p>
</section>
</div>
