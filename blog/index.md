---
layout: default 
permalink: /blog
title: "Blog"
image:
  feature: blog.jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
