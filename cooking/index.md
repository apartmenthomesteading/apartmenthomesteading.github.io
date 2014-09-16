---
layout: archive
title: "Cooking"
date: 2014-09-14
excerpt: "I try everything from crockpot meals to homemade roti."
image:
  feature: cooking-feature.jpg
  teaser: cooking-teaser.jpg
  thumb: cooking-teaser.jpg
  credit: ginnerobot #name of the person or site you want to credit
  creditlink: https://flic.kr/p/6ubVE1 #url to their site or licensing
ads: true
share: true
---


<div class="tiles">
{% for post in site.categories.cooking %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->