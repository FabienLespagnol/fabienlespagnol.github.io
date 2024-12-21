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
* 2020-2024: **PhD in Applied Mathematics.** _Politecnico di Milano / Sorbonne Université / Inria Paris._ France / Italie
* 2019-2020: **Master in Mathematical Modelling, Numerical Analysis and Simulation.** _Sorbonne Université / École Nationale des Ponts et Chaussées._ France.
  * Main topics: Theoretical and numerical study of partial differential equations; Numerical discretization and error analysis; Modelling and simulation in life sciences. 
* 2016-2020: **Engineering school - Computer Engineering and Mathematics.** _École Nationale des Ponts et Chaussées._ France.
  * Main topics: Theoretical and numerical study of partial differential equations; Optimization; Statistics; Machine Learning; Advanced computer science. 

Work experience
======
**Post-doctorate on homogenization and Hamilton’s principle for multiphase flows** 


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
