---
layout: page
title: MyBlog
---
<ul class="pots">
	{% for post in site.posts %}
		<li>{{ post.date | date_to_string }} <a href = "{{ baseurl }}{{ post.url }}">{{ post.title }}</a></li>
		<li>baseurl:{{ baseurl }}</li>
		<li>post.url:{{ post.url }}</li>
	{% endfor %}
</ul>