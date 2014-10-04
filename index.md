---
layout: archive
permalink: /
title: "Apartment Homesteading: Cooking, Gardening, Saving, and Prepping for my Future Tiny House"
image:
  feature: abandonedhomestead-text-2.jpg
  teaser: abandonedhomestead-teaser.jpg
  thumb: abandonedhomestead-teaser.jpg
  credit: Jim Fischer
  creditlink: https://flic.kr/p/cy9Qw1
---

<div class="tiles">
{% for post in site.posts %}
	{% if post.featured %}
		{% include post-grid.html %}
    {%endif%}
{% endfor %}
</div><!-- /.tiles -->
