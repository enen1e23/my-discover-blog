---
layout: page
title: Someday_Maybe
permalink: /categories/Someday_Maybe/
---

<h2>Someday_Maybe</h2>
<ul>
  {% for post in site.categories.Someday_Maybe %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small> — {{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
