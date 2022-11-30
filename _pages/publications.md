---
layout: page
permalink: /publications/
title: Publications
description: This is a list of selected proceedings and publications that I made significant contributions to. For a full list of publications, please visit my [inspire profile](https://inspirehep.net/authors/2127656). My Orchid ID is [0000-0003-0487-5595](https://orcid.org/0000-0003-0487-5595).
years: [2022, 2022, 2022]
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
