---
layout: archive
title: Quote
permalink: /quote
---

{% for post in site.categories.Quote %}
  <li><a href="{{ post.url }}">
    <p>{{ post.date | date: "%Y-%m-%d" }} » {{ post.title }}</p>
  </a></li>
{% endfor %}