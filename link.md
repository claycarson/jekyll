---
layout: page
title: Link
permalink: /link
---

# [Link](/link)
{% for post in site.categories.Link %}
  <li><a href="{{ post.url }}">
    <p>{{ post.date | date: "%Y-%m-%d" }} » {{ post.title }}</p>
  </a></li>
{% endfor %}