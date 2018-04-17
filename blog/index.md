---
title: Blog
permalink: "/blog"
layout: default
image:
  feature: blog.jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
