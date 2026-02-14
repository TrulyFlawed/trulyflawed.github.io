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
		<a href="{{ site.baseurl }}{{ post.url }}" class="article">
			<p class="title">{{ post.title }}</p>
			<div class="post-metadata">
				<!-- <p class="author">{{ post.author }}</p> -->
				<p class="date">{{ post.date | date: "%B %-d, %Y" }}</p>
			</div>
		</a>
	{% endfor %}
</div>