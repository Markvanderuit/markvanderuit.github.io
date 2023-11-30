---
layout: archive-cv
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

## Experience

- **PhD Student, Computer Graphics**<br>
  Jul 2020 - Present<br>
  Delft University of Technology<br>
- **Scientific Programmer**<br>
  Nov 2019 - June 2020<br>
  Delft University of Technology
- **Software Developer**<br>
  Mar 2016 - Oct 2019 (part time)<br>
  FSE Turnstiles
- **Web Developer**<br>
  Jul 2017 - Aug 2017 (part time)<br>
  Delft University of Technology
- **Technical Support**<br>
  Feb 2013 - Feb 2016 (part time)<br>
  Studentaanhuis.nl

## Education

- **PhD Computer Graphics** (expected)<br>
  Delft University of Technology, 2024/25
- **MSc Computer Science**<br>
  Delft University of Technology, 2019
- **Propadeutic Game Architecture**<br>
  Breda University of Applied Sciences, 2014
  
## Publications

{% for post in site.publications reversed %}
- **{{ post.title }}**<br>
  {{ post.venue }} ({{ post.conference }}), {{ post.bibtex.year }}
{% endfor %}

## Skills

- **General.** Computer graphics, 3D rendering, scientific research, problem solving.
- **Programming.** C++, OpenGL, GLSL, CUDA, LaTeX, CMake, Git.
  
## Languages

- **Dutch.** Native proficiency.
- **English.** Professional proficiency - Cambridge ESOL Level 3 Grade A.
- **German.** Basic proficiency - 5 years living and learning in Germany.

<!-- ## Publications

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Talks

  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->
