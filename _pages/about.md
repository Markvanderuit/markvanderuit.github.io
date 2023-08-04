---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi!

I'm a fourth-year PhD student at the [Computer Graphics & Visualization](https://graphics.tudelft.nl) group at the [TU Delft](https://www.tudelft.nl/). My research interests generally include offline rendering, spectral rendering, and high-dimensional data analysis. Together with my supervisor, [Elmar Eisemann](http://graphics.tudelft.nl/~eisemann/), I have worked on a variety of projects involving spectral importance sampling, artist-controllable spectral uplifting, and linear-runtime dimensionality reduction on the GPU.

During my research, I mostly work with OpenGL/C++, which leads to the occasional demos and renders. I've also picked up a liking for vector art, both in my publications and personal time. You can find plenty of examples throughout my portfolio and publications.

In my own time, I enjoy video games, fantasy/sci-fi reading, and running. I’m also a fan of tabletop RPGs and worldbuilding, so I run a few games as an occasionally grumpy game master. I don’t really use social networks, but if you’d like to chat, feel free to contact me!

## Recent publications

{% for post in site.publications reversed %}
  {% include archive-single-about.html %}
{% endfor %}