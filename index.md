---
layout: archive
permalink: /
title: "What I've Done So Far"
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

<h1 class="left">Still on my To-Do List</h1>

<div class="tiles">
{% for post in site.posts %}
	{% if post.to-do %}
		{% include post-grid.html %}
    {%endif%}
{% endfor %}
</div><!-- /.tiles -->