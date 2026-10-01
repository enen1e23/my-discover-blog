---
layout: page
title: Physics in Everyday Life
permalink: /categories/Physics_in_Everyday_Life/
---

生活中的物理发现：观察日常现象，尝试推导、实验与图解。

{% assign category_posts = site.categories.Physics_in_Everyday_Life %}

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
