---
layout: category
title: Italy
permalink: /italyCategory/
---

Test

<img src="http://www.trevifountain.net/images/trevifountain.jpg" width="80%" />

<ul class="postsWrapper">
{% for post in site.categories['italy'] %}
	<li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>