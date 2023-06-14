---
layout: page
permalink: /publications/
title: publications
description: publications by categories in reversed chronological order.
years: [2019, 2021, 2022, 2023]
to_publish: true
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>