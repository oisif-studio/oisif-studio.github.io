---
title: Team
permalink: "/team"
layout: default
image:
  feature: team.jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
