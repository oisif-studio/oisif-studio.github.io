---
title: Home
permalink: "/"
layout: home
image:
  feature: home.jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
