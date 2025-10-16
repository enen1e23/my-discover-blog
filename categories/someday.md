---
layout: page
title: Someday
permalink: /categories/someday/
---

<h2>Someday</h2>
<ul>
  {% for post in site.categories.someday %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small> — {{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
