---
layout: post
title: SaneryeeInSide by github
category:[lessons, beginner]
tags:[how-to, jekyll]
---
<ul class="pots">
	{% for post in site.posts %}
		<li>{{ post.date | date_to_string }} <a href = "{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</ul>