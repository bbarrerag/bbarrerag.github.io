---
layout: page
title: research
permalink: /research/
nav: true
nav_order: 2
---

<style>
  .post-header {
    display: none;
  }
</style>

A brief summary of the projects I have been most excited about during my PhD!

### Non-adiabatic Dynamics: Moving Beyond the Born-Oppenheimer Approximation

<img src="{{ '/assets/img/publication_preview/bucket.png' | relative_url }}"
     alt="The Moving Born-Oppenheimer approximation"
     style="float: right; width: 400px; margin: 0 0 1rem 1.5rem;">

Many systems in nature exhibit phenomena occurring on widely different timescales. This so-called *timescale separation* between slow and fast components often allows us to simplify the description of complex systems. An everyday example is a swinging bucket of water. If the bucket swings slowly, we can assume the water surface remains nearly horizontal, remaining in instantaneous equilibrium at every instant of time.

A century ago, Born and Oppenheimer applied this simple idea to molecular systems, where a similar timescale separation arises from the large difference between nuclear and electronic masses. Today, the [Born–Oppenheimer approximation](https://doi.org/10.1002/andp.19273892002) (BOA) remains a foundational method across both quantum chemistry and condensed matter physics. However, there are many settings in which it fails (e.g. in the computation of reaction rates and molecular spectra), and there is significant interest in developing robust methods to go beyond it.

A large part of my PhD has been devoted to developing techniques to describe systems beyond the Born-Oppenheimer limit. Drawing from ideas connecting quantum geometry and non-adiabatic response, we developed a systematic extension of the BOA that we termed the [Moving Born–Oppenheimer approximation](https://doi.org/10.1073/pnas.2507816123). We are very excited about exploring the consequences of this framework across a range of settings, including quantum chemistry, electron-phonon systems, and thinking about quantum geometry away from equilibrium. 

**Related publications**

- **B. Barrera**, D. P. Arovas, A. Chandran, and A. Polkovnikov, [*The Moving Born–Oppenheimer Approximation*](https://doi.org/10.1073/pnas.2507816123), PNAS **123**, e2507816123 (2026).
- **B. Barrera**, N. Verma, R. Queiroz, A. Polkovnikov, and A. Chandran, *Kinematic Quantum Geometry* (manuscript in preparation).


### Topology in Circuit QED

<img src="{{ '/assets/img/publication_preview/pump.png' | relative_url }}"
     alt="The Quantum Topological Photon Pump"
     style="float: right; width: 400px; margin: 0 0 1rem 1.5rem;">

Topology is an exciting tool for engineering quantum systems. Topological phenomena are robust, and can remain remarkably insensitive to the microscopic noise and imperfections that often abound in quantum systems.

*Topological photon pumps* exploit this principle to robustly transfer energy between two subsystems at a rate that is quantized and insensitive to details of the control protocol. In particular, they offer a promising route for reliably preparing non-classical states of a quantum cavity even in the presence of control imperfections.

In collaboration with the [Kollár group](https://kollarlab.umd.edu/) at the University of Maryland, we developed the first experimental realization of a quantum topological photon pump using a transmon qubit coupled to a microwave cavity. We further demonstrated operation of the pump in the quantum regime: starting from the vacuum, the pump transfers energy into the cavity up to a photon number of approximately $n\approx 7$, and produces demonstrably non-classical cavity states for the first few cycles.

**Related publications**

- Q. Yue, **B. Barrera**, M. Ritter, D. M. Long, D. A. Lane, A. Chandran, and A. J. Kollár, [*Realization of a quantum topological photon pump*](https://arxiv.org/abs/2608.00162), (2026). https://arxiv.org/abs/2608.00162.
