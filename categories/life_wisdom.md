---
layout: page
title: life_wisdom
permalink: /categories/life_wisdom/
---

<h2>life_wisdom</h2>
<ul>
  {% for post in site.categories.life_wisdom %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small> — {{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
