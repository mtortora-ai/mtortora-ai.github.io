---
layout: page
permalink: /publications/
title: publications
description:
years: [2023, 2022, 2021]
nav: true
---
An up-to-date list is available on [Google Scholar](https://scholar.google.it/citations?user=3WpZse0AAAAJ&hl=en&oi=ao)
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
