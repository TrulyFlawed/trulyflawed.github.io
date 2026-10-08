---
title: "Blog"
layout: default
permalink: /blog/
description: "The smaller, unstructured writings of mine."
---
# Blog

For random thoughts.

<div class="article-list">
	{% for post in site.posts %}
		{% assign meta_description = post.description
		| default: post.excerpt
		| default: site.description
		| strip_html
		| normalize_whitespace
		| truncate: 160 %}

		<a href="{{ site.baseurl }}{{ post.url }}" class="article">
			<p class="title">{{ post.title }}</p>
			<p class="subtitle">{{ meta_description | escape }}</p>
			<div class="post-metadata">
				<p class="date">{{ post.date | date: "%B %-d, %Y" }}</p>
			</div>
		</a>
	{% endfor %}
</div>