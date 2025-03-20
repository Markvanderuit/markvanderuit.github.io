---
title      : "Controlled Spectral Uplifting for Indirect-Light-Metamerism"
collection : publications
permalink  : /publications/2024-11-19-paper-spectral
date       : 2024-11-19
venue      : 'SIGGRAPH Asia Conference Papers'
conference : 'SIGGRAPH Asia'
paperurl   : 'https://markvanderuit.github.io/files/2024-11-19-paper-spectral/spectral-paper.pdf'
journalurl : 'https://doi.org/10.1145/3680528.3687698'
codeurl    : 'https://github.com/markvanderuit/metameric_dev'
videourl   : 'https://markvanderuit.github.io/files/2024-11-19-paper-spectral/spectral-editing.mp4'
image      : '../images/publications/control-teaser.png'
bibtex     :
  name       : 'RuitEisemann2024'
  author     : 'Mark van de Ruit and Elmar Eisemann'
  year       : '2024'
  month      : 'nov'
  publisher  : 'ACM'
  doi        : '10.1145/3680528.3687698'
  journal    : 'SIGGRAPH Asia 2024 Conference Papers'
---

> This page mirrors the [CGV group page](https://graphics.tudelft.nl/Publications-new/2024/RE24/).

## Abstract

Spectral rendering has received increasing attention in recent years. Yet, solutions to define spectral reflectances are mostly limited to uplifting techniques which deterministically augment existing RGB inputs. Only recently has uplifting been able to ensure a certain surface appearance under direct illuminants. Yet, prior work in this area limits artist expressiveness and is not well suited for designing the appearance of a scene, as indirect illumination is ignored entirely.

We present an uplifting technique with fine-grained spectral appearance control under direct and indirect illumination, even enabling the placement of spectral constraints in a specific scene. Our approach allows for a flexible authoring process, and solves for the resulting spectra efficiently. Additionally, we show that our method's memory overhead during rendering is kept small, by introducing a compact spectral texture format.

{% include single_publication_bibtex.md %}