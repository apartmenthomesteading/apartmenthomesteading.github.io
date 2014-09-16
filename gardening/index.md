---
layout: archive
title: "Gardening"
date: 2014-09-14
excerpt:  "Microgreens, miracle fruit, and grow lights."
image:
  feature: container-garden-feature.jpg
  teaser: container-garden-teaser.jpg
  thumb: container-garden-teaser.jpg
ads: true
share: true
---

<div class="tiles">
{% for post in site.categories.gardening %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->