---
layout: category
title: Italy
permalink: /italy-category/
---

Test

<ul class="postsWrapper">
{% for post in site.categories['italy'] %}
	<li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>