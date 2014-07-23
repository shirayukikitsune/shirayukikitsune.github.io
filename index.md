---
layout: page
title: Shirayuki Kitsune Dev Blog
---
{% include JB/setup %}

<div class="blog-index">  
	{% assign post = site.posts.first %}
	{% assign content = post.content %}
	<h1 class="entry-title">
	{% if post.title %}
		<a href="{{ root_url }}{{ post.url }}">{{ post.title }}</a>
	{% endif %}
	</h1>
	<div class="entry-content">{{ content }}</div>
	
	<a href="{{ root_url }}{{ post.url }}#comment">Click here to comment</a>
</div>
