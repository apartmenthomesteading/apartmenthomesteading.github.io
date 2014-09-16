---
layout: archive
permalink: /
title: "Latest Posts"
image:
  feature: abandonedhomestead-feature.jpg
  teaser: abandonedhomestead-teaser.jpg
  thumb: abandonedhomestead-teaser.jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->