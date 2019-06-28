---
layout: page
title: Blog
permalink: /blog/
---

<ul>
{% for p in site.posts %}
  <li><a href="{{ p.url }}"><span class="post-title">{{ p.title }}</span></a>
  {{p.excerpt}}</li>
{% endfor %}
</ul>
