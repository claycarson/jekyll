---
layout: default
---

# [location](/location)
{% for post in site.categories.location %}
  <li><a href="{{ post.url }}">
    <p>{{ post.title }}</p>
  </a></li>
{% endfor %}