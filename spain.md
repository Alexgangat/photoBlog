---
layout: category
title: Spain
permalink: /spain-Category/
---





<ul class="postsWrapper">
{% for post in site.categories['spain'] %}
	<li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>