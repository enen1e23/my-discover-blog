---
layout: page
title: Life_Wisdom
permalink: /categories/Life_Wisdom/
---
<ul>
  {% for post in site.categories.Life_Wisdom %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small> — {{ post.date | date: "%Y-%m-%d" }}</small></li>
  {% endfor %}
</ul>
