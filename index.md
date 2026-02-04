---
title: "Home"
layout: "default"
---
# Dusk writes mini essays on knowledge management and tech.

Web developer, writer, and designer.

## Blog

<!-- Automatically generate list of blog posts. -->
<div class="article-list">
	{% for post in site.posts %}
		<div class="article">
			<a href="{{ site.baseurl }}{{ post.url }}" class="center">{{ post.title }}</a>
			<div class="post-metadata">
				<!-- <div class="author">{{ post.author }}</div> -->
				<div class="date">{{ post.date | date: "%B %-d, %Y" }}</div>
			</div>
		</div>
	{% endfor %}
</div>