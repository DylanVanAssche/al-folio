---
layout: page
permalink: /publications/
title: Publications
description: My research articles and other publications, chronological ordered.
years: [2019]
---

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
