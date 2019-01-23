---
layout: archive
title: Location
permalink: /location
---

{% for post in site.categories.Location %}
<ul>
  <li>
    <p>{{ post.date | date: "%Y-%m-%d" }} » <a href="{{ post.url }}">{{ post.excerpt | strip_html }}</a></p>
  </li>
</ul>  
{% endfor %}