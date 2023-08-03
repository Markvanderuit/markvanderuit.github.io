---
title      : "Metameric: Spectral Uplifting via Controllable Color Constraints"
collection : publications
permalink  : /publications/2023-07-23-paper-metameric
date       : 2023-07-23
venue      : 'Siggraph Conference Proceeedings'
paperurl   : 'https://markvanderuit.github.io/files/2023-07-23-paper-metameric.pdf'
demourl    : 'https://markvanderuit.github.io/files/2023-07-23-paper-metameric.zip'
citation   : 'Mark van de Ruit and Elmar Eisemann. 2023.'
image      : '../images/publications/metameric-teaser.png'
bibtex     :
  name       : 'RuitEisemann2023'
  author     : 'Mark van de Ruit and Elmar Eisemann'
  year       : '2023'
  month      : 'jul'
  publisher  : 'ACM'
  doi        : '10.1145/3588432.3591565'
  journal    : 'SIGGRAPH 2023 Conference Proceedings'
---

## Abstract

Spectral rendering is a crucial solution for photorealistic rendering.
However, most available texture assets are RGB-only, and access to spectral content is limited.
Uplifting methods that recover full spectral representations from RGB inputs have therefore received much attention.
Yet, most methods are deterministic, while, in reality, there is no one-to-one mapping.
As a consequence, the appearance of uplifted textures is fully determined under all illuminants.
Hereby, metamers, which are materials with differing spectral responses that appear identical under a specific illumination, are excluded.
We propose a method which makes this uplifting process controllable.
Hereby, a user can define texture appearance under various lighting conditions, leading to a greatly increased flexibility for content design.
Our method determines the space of possible metameric manipulations and enables interactive adjustments, while maintaining a set of user-specified appearance constraints.
To achieve this goal, we formulate the problem as a constrained optimization, building upon an interpolation scheme and data-based reflectance generation, which maintain plausibility.
Besides its value for artistic control, our solution is lightweight and can be executed on the fly, which keeps its memory consumption low and makes it easy to integrate into existing frameworks.

{% include single_publication_bibtex.md %}
