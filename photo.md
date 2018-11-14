---
layout: default
---

# [photo](/photo)
{% for post in site.categories.photo %}
  <li><a href="{{ post.url }}">
    <p>{{ post.title }}</p>
  </a></li>
{% endfor %}