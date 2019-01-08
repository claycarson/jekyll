---
layout: default
title: Status
permalink: /status
---

# [Status](/status)
{% for post in site.categories.Status %}
  <li><a href="{{ post.url }}">
    <p>{{ post.date | date: "%Y-%m-%d" }} » {{ post.excerpt | strip_html }}</p>
  </a></li>
{% endfor %}