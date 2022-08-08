---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Full CV
======
Download [CV](http://duongnguyen1601.github.io/files/CV.pdf)

Education
======
* Ph.D Student in Electrical Engineering, Arizona State University, 2021 - present
* M.S. in Applied Mathematics, University of Louisiana at Lafayette, 2019
* B.S. in Mathematics, Dalat University, 2017

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
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

