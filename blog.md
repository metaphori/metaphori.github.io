---
layout: page
title: Blog
permalink: /blog/
---

<ul>
{% for p in site.posts %}
  <li><a href="{{ p.url }}">{{ p.title }}</a>{{p.excerpt}}</li>
{% endfor %}
</ul>
