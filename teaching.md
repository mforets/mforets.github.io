---
layout: page
title: Teaching
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{post.content}}
    </li>
  {% endfor %}
</ul>
