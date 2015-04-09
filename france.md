---
layout: category
title: France
permalink: /france-Category/
---

<ul class="postsWrapper">
{% for post in site.categories['france'] %}
	<li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>