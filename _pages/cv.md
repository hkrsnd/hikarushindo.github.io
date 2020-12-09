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
* B.S. in Kyoto University, Japan, 2018
* M.S. in Kyoto University, Japan, 2020

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Employment
======
* Apr 2020 - Oct 2020 : Research Fellow at Japan Society for the Promotion of Science
  * JSPS DC1

* Nov 2020 - : Research Associate at TU Darmstadt
  * Wissenshaftlicher Mitarbeiter (E13)
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
