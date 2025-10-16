---
layout: page
title: Physics_in_Everyday_Life
permalink: /categories/Physics_in_Everyday_Life/
---
<ul>
  {% for post in site.categories.Physics_in_Everyday_Life %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small> — {{ post.date | date: "%Y-%m-%d" }}</small></li>
  {% endfor %}
</ul>
