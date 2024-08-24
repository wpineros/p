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
* Ph.D in theoretical chemistry, University of Texas at Austin, 2018
* B.S. in Physics, State University of New York at Buffalo, 2012
* B.A. in chemistry, City University of New York, Queens college, 2010

Work experience
======
* 09/2023-Present:
  * Marie-Curie Post-doctoral Fellow
  * University of Luxembourg
  * Advisor: E. Fodor

* 05/2022-09/2023:
  * Post-doctoral researcher
  * University of Luxembourg
  * Advisor: E. Fodor

* 04/2019-04/2022:
  * post-doctoral researcher
  * Institute of Basic Science, South Korea
  * Advisor: T. Tlusty


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
