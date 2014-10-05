---
layout: archive
title: "Tiny House Plans"
date: 2014-09-14
excerpt: "Here's how I'm planning to build my tiny house."
image:
  feature: tinyhouse-feature.jpg
  teaser: tinyhouse-teaser.jpg
  thumb: tinyhouse-teaser.jpg
  credit: Tammy Strobel
  creditlink: https://flic.kr/p/dKrndr
ads: true
share: true
comments: true
---

<div class="tiles">
{% for post in site.categories.tiny-house %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
