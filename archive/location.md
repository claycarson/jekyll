---
layout: archive
title: Location
permalink: /location
---

{% for post in site.categories.Location %}
  <li>
    <p>{{ post.date | date: "%Y-%m-%d" }} » <a href="{{ post.url }}">{{ post.excerpt | strip_html }}</a></p>
  </li>
{% endfor %}