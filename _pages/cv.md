---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

For the most updated full version of my CV please download at:
<p><a href="{{ base_path }}/files/CV.pdf" target="_blank" rel="noopener">Download my CV (PDF)</a></p>

Education
======
* Ongoing Ph.D in Physics, Harvard University, 2027 (expected)
* B.S. in Mathematics, University of Chicago, 2021
* B.A. in Physics, University of Chicago, 2021
* Minor in Computer Science, University of Chicago, 2021

Awards and Recognitions
======
* Gertrude and Maurice Goldhaber Prize, Harvard University, 2025
* White Prize, Havard University, 2023
* Student Recognition of Teaching, Harvard University, 2023
* Magna Cum Laude, The University of Chicago, 2021

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
