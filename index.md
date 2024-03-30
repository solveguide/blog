---
layout: default
title: Home
---

# Solve Guide Blog

My thoughts while developing Solve Guide.


{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
