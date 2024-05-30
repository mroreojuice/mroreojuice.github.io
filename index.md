---
layout: default
title: Home
---

# Welcome to My Blog

Hello! This is my blog where I share my thoughts and experiences.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>

