---
title: "Simulating the 3D Ising model"
excerpt: "A simulation of the three-dimensional Ising model using both Simulated Annealing and the Wolff cluster algorithm."
collection: portfolio
---

A simulation of the **three-dimensional Ising model**, implemented with two different sampling strategies so their behaviour can be compared directly:

* **Simulated annealing** — single-spin updates under a temperature schedule that is gradually lowered towards the ground state.
* **The Wolff algorithm** — a cluster method that flips whole correlated regions of spins at once. This matters near the critical temperature, where single-spin methods suffer from critical slowing down and the correlation time blows up; flipping clusters largely avoids that.

The Ising model is the standard testbed for phase transitions in statistical physics, and the contrast between a local and a cluster update rule is a clean illustration of why algorithm choice, not just compute, determines whether a simulation is usable near criticality.

**Code:** [github.com/TomGiaco/Simulation-3D-Ising-Model](https://github.com/TomGiaco/Simulation-3D-Ising-Model)
