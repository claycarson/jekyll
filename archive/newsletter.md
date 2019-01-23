---
layout: archive
title: Newsletter
permalink: /newsletter
---

{% for post in site.categories.Newsletter %}
<ul>
  <li><a href="{{ post.url }}">
    <p>{{ post.title }}</p>
  </a>
  </li>
</ul>  
{% endfor %}