---
layout: page
title: Physics in Everyday Life
permalink: /categories/physics_in_everyday_life/
---

<h2>Physics in Everyday Life</h2>
<ul>
  {% for post in site.categories.physics_in_everyday_life %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small> — {{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
