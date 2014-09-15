---
layout: archive
title: "Philosophy"
date: 2014-09-14
excerpt:  "Stoicism, self-sufficiency, and back-to-the-land tendencies."
image:
  feature: painted-desert-feature.jpg
  teaser: painted-desert-feature.jpg
  thumb: painted-desert-feature.jpg
ads: true
share: true
---
<div class="tiles">
{% for post in site.categories.philosophy %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->