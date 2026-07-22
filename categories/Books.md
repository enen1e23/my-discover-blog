---
layout: page
title: Books
permalink: /categories/Books/
---

我觉得值得读的英文书，以及慢慢完成的分节翻译。

---

{% assign book_posts = site.categories.Books %}

{% if book_posts and book_posts.size > 0 %}
<ul>
  {% for post in book_posts %}
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