---
layout: default
---

# [Status](/status)
{% for post in site.categories.status %}
  <li><a href="{{ post.url }}">
    <p>{{ post.title }}</p>
  </a></li>
{% endfor %}