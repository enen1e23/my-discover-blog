---
layout: page
title: Physics in Everyday Life
permalink: /categories/Physics_in_Everyday_Life/
nav_exclude: true
---

📐 生活里的物理小发现：记录我对日常现象的好奇与推导。

---

{% if site.categories.Physics_in_Everyday_Life %}
  {% for post in site.categories.Physics_in_Everyday_Life %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
  {% endfor %}
{% else %}
*暂无文章，敬请期待~*
{% endif %}

---

[← 返回分类](/categories/) · [← 返回首页](/)
