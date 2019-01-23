---
layout: archive
title: Status
permalink: /status
---

{% for post in site.categories.Status %}
<ul>
  <li>
    <p>{{ post.date | date: "%Y-%m-%d" }} » <a href="{{ post.url }}">{{ post.excerpt | strip_html }}</a></p>
  </li>
</ul>  
{% endfor %}