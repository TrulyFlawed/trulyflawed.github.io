---
title: "Blog"
layout: default
permalink: /blog/
---
# Blog

For random thoughts.

<div class="article-list">
	{% for post in site.posts %}
		<a href="{{ site.baseurl }}{{ post.url }}" class="article">
			<p class="title">{{ post.title }}</p>
			<div class="post-metadata">
				<p class="date">{{ post.date | date: "%B %-d, %Y" }}</p>
			</div>
		</a>
	{% endfor %}
</div>