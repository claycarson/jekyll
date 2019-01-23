---
layout: archive
title: Media
permalink: /media
---

{% for post in site.categories.Media %}
  <li>
    <p>{{ post.date | date: "%Y-%m-%d" }} » <a href="{{ post.url }}">{{ post.excerpt | strip_html }}</a></p>
  </li>
{% endfor %}