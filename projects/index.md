---
layout: default 
permalink: /projects
title: "Projects"
image:
  feature: projects.jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
