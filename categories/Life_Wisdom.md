---
layout: page
title: Notes on Living
permalink: /categories/Life_Wisdom/
---

普通生活中的经验、方法和点滴发现。

{% assign category_posts = site.categories.Life_Wisdom %}

{% if category_posts.size > 0 %}
<ul>
{% for post in category_posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a> — <time datetime="{{ post.date | date: '%Y-%m-%d' }}">{{ post.date | date: "%Y-%m-%d" }}</time></li>
{% endfor %}
</ul>
{% else %}
这里还没有文章，慢慢积累。
{% endif %}

---

[← 全部分类]({{ "/categories/" | relative_url }}) · [返回首页]({{ "/" | relative_url }})
