---
title: "Home"
layout: "default"
---
# Dusk writes mini essays on knowledge management and tech.

Web developer, writer, and designer.

## Blog

<div class="article-list">
	{% for post in site.posts limit: 4 %}
		<a href="{{ site.baseurl }}{{ post.url }}" class="article">
			<p class="title">{{ post.title }}</p>
			<div class="post-metadata">
				<p class="date">{{ post.date | date: "%B %-d, %Y" }}</p>
			</div>
		</a>
	{% endfor %}

	<a href="/blog" class="basic-link">See all blog posts</a>
</div>