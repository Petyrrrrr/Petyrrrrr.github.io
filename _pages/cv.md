---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can find my CV here.

Education
======
* B.S. in GitHub, GitHub University, 2012
* M.S. in Jekyll, GitHub University, 2014
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)

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

Work experience
======
* Summer 2021: Quantitative Research Intern, TongDeng Fund (Shanghai China)
  * Worked on position optimizing algorithm based on T+1 stock market constraint.

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
