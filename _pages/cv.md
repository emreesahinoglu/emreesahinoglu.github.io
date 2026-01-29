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
* Ph.D in Industrial Engineering, Northeastern University, 2027 (expected)
* B.S. in Electrical and Electronics Engineering, Bilkent University, 2017

Work experience
======
* 2018-2021: Machine Learning Engineer
  * ASELSAN

* 2021-2022: Quantitative Researcher
  * Morphy Capital
  

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
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

