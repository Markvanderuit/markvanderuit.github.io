---
title      : "A Multi-Pass Method for Accelerated Spectral Sampling"
collection : publications
permalink  : /publications/2021-11-27-paper-spectral
date       : 2021-11-27
venue      : 'Computer Graphics Forum'
conference : 'Pacific Graphics'
paperurl   : 'https://markvanderuit.github.io/files/2023-07-23-paper-metameric.pdf'
image      : '../images/publications/spectral-teaser.png'
bibtex     :
  name       : 'RuitEisemann2021'
  author     : 'Mark van de Ruit and Elmar Eisemann'
  year       : '2021'
  month      : 'nov'
  publisher  : 'Wiley'
  doi        : '10.1111/cgf.14408'
  journal    : 'Computer Graphics Forum'
---

## Abstract

Spectral Monte Carlo rendering can simulate advanced light phenomena, such as chromatic dispersion, but typically shows a slow convergence behavior. Properly sampling the spectral domain can be challenging in scenes with many complex spectral distributions. To this end, we propose a multi-pass approach. We build and store coarse screen-space estimates of incident spectral radiance and use these to then importance sample the spectral domain. Hereby, we lower variance and reduce noise with little overhead. Our method handles challenging scenarios with difficult spectral distributions, many different emitters, and participating media. Finally, it can be integrated into existing spectral rendering methods for an additional acceleration.


{% include single_publication_bibtex.md %}
