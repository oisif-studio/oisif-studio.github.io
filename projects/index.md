---
title: Projects
permalink: "/projects"
layout: default
image:
  feature: projects.jpg
---

<div class="tiles">
{% for post in site.categories.project %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
