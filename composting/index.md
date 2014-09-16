---
layout: archive
title: "Composting"
date: 2014-09-14
excerpt: "Brown + Green + Water + Air = ? "
image:
  feature: compost-feature.jpg
  teaser: compost-teaser.jpg
  thumb: compost-teaser.jpg
  creditlink: https://flic.kr/p/7Sbyv9
  credit: Lindsay

ads: true
share: true
---

<div class="tiles">
{% for post in site.categories.composting %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->