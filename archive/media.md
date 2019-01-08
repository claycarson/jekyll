---
layout: default
title: Media
permalink: /media
---

# [Media](/media)
{% for post in site.categories.Media %}
  <li><a href="{{ post.url }}">
    <p>{{ post.date | date: "%Y-%m-%d" }} » {{ post.excerpt | strip_html }}</p>
  </a></li>
{% endfor %}