---
layout: page
permalink: /publications/
title: publications
description:  
years: [2021, 2020, 2019, 2018]
nav: true
---
[\*]() denotes equal contribution

An up-to-date list is available on [Google Scholar](https://scholar.google.com/citations?user=517t5gEAAAAJ).

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

