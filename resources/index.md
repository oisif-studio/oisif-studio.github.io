---
title: Resources
permalink: "/resources"
layout: default
image:
  feature: team.jpg
---

<div class="tiles">
{% for post in site.categories.resource %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
