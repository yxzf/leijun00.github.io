---
layout: archive
permalink: /math/
title: "Latest Posts in Math"
excerpt: "I make living from IT"
---

<div class="tiles">
{% for post in site.posts %}
	{% if post.categories contains 'math' %}
		{% include post-grid.html %}
	{% endif %}
{% endfor %}
</div><!-- /.tiles -->