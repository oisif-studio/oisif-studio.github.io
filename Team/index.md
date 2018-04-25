---
layout: default 
permalink: /team
title: "Team"
image:
  feature: team.jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
