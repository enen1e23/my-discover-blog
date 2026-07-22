---
layout: page
title: Cities
permalink: /categories/Cities/
---

我看到的城市。

---

{% assign city_posts = site.categories.Cities %}

{% if city_posts and city_posts.size > 0 %}
<ul>
  {% for post in city_posts %}
    <li>
      <a href="{{ post.url | relative_url }}">
        {{ post.title }}
      </a>
      — {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>
{% else %}
这里还没有文章。
{% endif %}

---

[← 返回首页]({{ '/' | relative_url }})