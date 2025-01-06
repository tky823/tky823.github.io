---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

- M.S in Information Science and Technology, Mar. 2020.
  Graduate School of Information Science and Technology, The University of Tokyo, Japan,
- B.S in Science and Engineering, Mar. 2020.
  Department of Communications and Computer Engineering, School of Fundamaneta Science and Engineering, Waseda University, Japan.

Work experience
======
- Oct. 2023-: LY Corporation
  - Music processing

- April 2022: LINE
  - Speech synthesis
  - Music processing

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
