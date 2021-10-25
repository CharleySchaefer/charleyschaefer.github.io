---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

<img src="https://github.githubassets.com/images/modules/open_graph/github-mark.png" alt="drawing" width="100"/> 

The software that I develop and use for my research is (when possible) shared in public github repositories; these will be summarised on this page.
Software that is not yet publicly shared (but of which the output is used in my publications) is usually available on request.



AggresomeIPBM
---
[AggresomeIPBM](https://github.com/CharleySchaefer/AggresomeIPBM) simulates the collective dynamics of protein using a kinetic Monte Carlo algorithm.
In [X. Jin et al., Science Adv. 7, 43 (2021)](https://www.science.org/doi/10.1126/sciadv.abh2929) this software was used to simulate the LLPS of proteins, as well as the fluorescence recovery after photobleaching (FRAP), in living bacteria.

Bombyx
---
[Bombyx](https://github.com/CharleySchaefer/Bombyx) uses a brute-force algorithm to fit the *sticky-reptation* model to the measured linear-viscoelastic response of silk feedstock, produced by the *Bombyx mori* silkworm.
The code is written in C, and its output is peer reviewed in the scientific publication [Schaefer et.,  Macromolecules 2020](https://pubs.acs.org/doi/abs/10.1021/acs.macromol.9b02630). I aim to improve the algorithm further, and implement it into RepTate (see below).

MorusMD
---
[MorusMD](https://github.com/CharleySchaefer/MorusMD1D) simulates the coarse-grained molecular dynamics of sticky polymers in flow in 1D.
The simulation output is peer reviewed in the scientific publication [*Schaefer & McLeish, Phys. Rev. Lett (2021)*](https://doi.org/10.1103/PhysRevLett.126.057801).

RepTate (contribution)
---
[RepTate](https://reptate.readthedocs.io/) is a software package that enables to analyse experimental (typically rheological) data using state-of-the-art polymer-physics models.
The package was developed by the polymer-physics community of the United Kingdom.
While my contribution of implementing the [sticky reptation model](https://reptate.readthedocs.io/manual/Applications/LVE/Theory/theory.html#sticky-reptation) is modest, I find new future contributions very likely.


ZiltoidLIB
---
[ZiltoidLIB](https://github.com/CharleySchaefer/ZiltoidLIB) is my personal, but publicly shared, C/C++ library.
