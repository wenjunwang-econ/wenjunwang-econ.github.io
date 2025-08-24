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
* Ph.D in Agricultural and Resource Economics, University of Maryland-College Park, 2018
* M.S. in Finance, Renmin University of China, 2013
* B.S. in Finance, Renmin University of China, 2010

Work experience
======
* 2018-2025: Research Economist
  * Investment Banking Department, Agricultural Bank of China

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
  
