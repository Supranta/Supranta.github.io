---
layout: page
permalink: /publications/
title: Publications
description: Publications and preprints
status: [In Preparation, Preprints, Published]
---

{% for s in page.status %}
  <h3 class="year">{{s}}</h3>
  {% bibliography -f papers -q @*[year={{s}}]* %}
{% endfor %}
