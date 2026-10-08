---
title: "Home"
layout: "default"
---
# Dusk writes mini essays on knowledge management and tech.

Web developer, writer, and designer.

## Recent posts

<div class="article-list">
	{% for post in site.posts limit: 4 %}
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
<div class="blog-redirect-button">
	<a href="/blog" class="basic-link">See all blog posts</a>
</div>