---
layout: default
title: AI Mirrors
permalink: /mirror/
---

<h1>AI Mirrors</h1>

<ul>
  {% for post in site.categories.mirror %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
