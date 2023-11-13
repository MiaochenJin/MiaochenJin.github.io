---
layout: page
permalink: /publications/
title: Publications
description: This is a list of selected proceedings and publications that I made significant contributions to. For a full list of publications, please visit my <a href='https://inspirehep.net/authors/2127656' style='color:#3366CC'>inspire profile</a>. My Orchid ID is <a href='https://orcid.org/0000-0003-0487-5595' style='color:#3366CC'>0000-0003-0487-5595</a>.
years: [2023, 2022]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
