---
layout: page
title: Low-dimensional firing rate models
description: spectral decomposition of the refractory density
img: /assets/img/lowdim_cover.png
---


<div>  
<p>Higher brain functions, such as sensory information processing and the attendant complexities of learning, memory storage, and pattern recognition, rely on the orchestrated interplay of a large number of neurons.
Through their collective dynamics, structure emerges in large-scale spatiotemporal brain activity and information can be introduced into the nervous system.
</p><p style="float: right;"><img src="{{ site.baseurl }}/assets/img/activity_fig.png" alt="" title="overview" style="float: left" width="400px" height="auto" padding="1px"></p>  
</div>
A major goal of neuroscience, statistical physics, and nonlinear dynamics is to understand how brain
function arises from the collective dynamics of networks of spiking neurons. This challenge has been
chiefly addressed through large-scale numerical simulations. Alternatively, researchers have formulated
mean-field theories to gain insight into macroscopic states of large neuronal networks in terms of the
collective firing activity of the neurons, or the firing rate.


<br>
To describe the collective dynamics of large populations of neurons, one often resorts to traditional firing-rate, or neural-mass, models. These models are low-dimensional and therefore analytically tractable. But they are also heuristic and cannot capture more complex dynamics of stochastic spiking neurons.


Fundamentally, these theories have not succeeded in
establishing an exact correspondence between the firing rate of the network and the underlying microscopic
state of the spiking neurons. This has largely constrained the range of applicability of such macroscopic
descriptions, particularly when trying to describe neuronal synchronization.

<div><p style="float: left;"><img src="http://placekitten.com/g/200/200" height="200px" width="200px" border="1px"></p>
<p>Text Text Text Text Text Text Text Text Text Text Text Text Text Text Text Text Text Text Text</p>
</div>

<br>
Here, we will present a systematic reduction of the population activity of general renewal-type neurons that can account for neuronal refractoriness and spike synchronization dynamics.
<div class="img_row">
    <embed class="col three left" src="{{ site.baseurl }}//assets/img/PAR_network.png" alt="" title="overview" max-width="600px" height="auto">
</div>

<br>

The derivation is based on an eigenmode expansion of the associated refractory density equation. Already a first-order approximation yields an accurate low-dimensional firing rate model that captures spike synchronization effects and fast transient dynamics at stimulus onset. The characteristic time scales of the system can be determined through a simple eigenvalue formula in terms of the interspike interval density or the survival function of the renewal process. The eigenvalue formula thus directly links microscopic neuronal properties to observed macroscopic behavior. 
Last, as our approach generalizes previous spectral methods for Fokker-Planck equations to arbitrary renewal models, we obtain equivalent firing rate dynamics for integrate-and-fire models driven by white noise in an alternative, but more elegant way.

