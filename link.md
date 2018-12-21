---
layout: page
title: Link
permalink: /link
---

<a href="/link">Link</a>
{% for post in site.categories.link %}
  <li><a href="{{ post.url }}">
    <p>{{ post.title }}</p>
  </a></li>
{% endfor %}