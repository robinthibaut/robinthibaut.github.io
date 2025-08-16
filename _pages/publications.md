---
layout: page
permalink: /publications/
title: publications
description: Complete list of publications, conference presentations, and software contributions.
years: [2025, 2024, 2023, 2022, 2021, 2020, 2019]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

## Peer-Reviewed Articles & Thesis

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f citations -q @article[year={{y}}] %}
  {% bibliography -f citations -q @phdthesis[year={{y}}] %}
{% endfor %}

## Conference Presentations

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f citations -q @inproceedings[year={{y}}] %}
{% endfor %}

## Software & Data Contributions

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f citations -q @software[year={{y}}] %}
  {% bibliography -f citations -q @misc[year={{y}}] %}
{% endfor %}

</div>
