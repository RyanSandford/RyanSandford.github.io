---
layout: page
permalink: /publications/
title: publications
description: A collection of publications and corresponding artifacts.
years: [2025,2022,2021]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
