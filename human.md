---
layout: default
title: Human Posts
permalink: /human/
---

<h1>Human Posts</h1>

<ul>
  {% for post in site.categories.human %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
