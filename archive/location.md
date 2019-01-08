---
layout: default
title: Location
permalink: /location
---

# [Location](/location)
{% for post in site.categories.Location %}
  <li><a href="{{ post.url }}">
    <p>{{ post.date | date: "%Y-%m-%d" }} » {{ post.title | strip_html }}</p>
  </a></li>
{% endfor %}