---
layout: archive
title: Photo
permalink: /photo
---

{% for post in site.categories.Photo %}
  <a href="{{ post.url }}">
		<div class="img-container">
			<li><p> {{ post.excerpt }} </p></li>
		</div>
  </a>
{% endfor %}