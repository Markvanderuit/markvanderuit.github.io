---
permalink: /
layout: simple_page
image: '../images/about-teaser.jpg'
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm an avid computer scientist and graphics programmer, currently wrapping up my PhD at the [Computer Graphics & Visualization](https://graphics.tudelft.nl) group at [TU Delft](https://www.tudelft.nl/). 
My interests have varied from online/offline/spectral rendering to artist-friendly tooling, complex GPU algorithms and high-dimensional data analysis.

I relish tackling problems for which no efficient solution (yet) exists, greatly enjoy learning from my colleagues in the field, and am always exploring new topics, whether it's software frameworks, algorithmic approaches, or any part of the graphics pipeline.
I mostly work with C++, OpenGL, and occasionally Vulkan.

In my own time, I enjoy video games, fantasy/sci-fi novels, and running.
I'm also a huge fan of tabletop RPGs and worldbuilding, so I run a few games as an occasionally grumpy game master.

If you'd like to chat, feel free to reach out!

## Recent publications

{% for post in site.publications reversed %}
  {% include archive-single-about.html %}
{% endfor %}