---
layout: page
permalink: /publications/
title: Publications
description: >
  Top publications are <span class="myabbr"><abbr class="badge">highlighted</abbr></span>

years: [2020, 2019, 2018, 2017, 2016, 2015]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
