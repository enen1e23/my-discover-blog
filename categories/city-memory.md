---
layout: page
title: 城市怎样记住自己
permalink: /categories/Cities/city-memory/
---

{% assign memory_posts = site.categories.Cities | where: "section", "reading-the-city" | where: "topic", "city-memory" %}

{% if memory_posts.size > 0 %}
<ul>
{% for post in memory_posts %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a> — <time datetime="{{ post.date | date: '%Y-%m-%d' }}">{{ post.date | date: "%Y-%m-%d" }}</time></li>
{% endfor %}
</ul>
{% else %}
还没有文章，慢慢积累。
{% endif %}

---

[← 返回看见城市]({{ '/categories/Cities/' | relative_url }})
