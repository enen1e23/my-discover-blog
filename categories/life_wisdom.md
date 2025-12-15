---
layout: page
title: Life Wisdom
permalink: /categories/Life_Wisdom/
nav_exclude: true
---

💡 人民群众的智慧：朴素经验、生活方法与点滴启发。

---

{% if site.categories.Life_Wisdom %}
  {% for post in site.categories.Life_Wisdom %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%Y-%m-%d" }}
  {% endfor %}
{% else %}
*暂无文章，敬请期待~*
{% endif %}

---

[← 返回分类]({{ "/categories/" | relative_url }}) · [← 返回首页]({{ "/" | relative_url }})
