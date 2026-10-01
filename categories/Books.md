---
layout: page
title: Reading
permalink: /categories/Books/
---

我读过、愿意推荐的书，以及围绕一个问题慢慢展开的阅读。

{% assign category_posts = site.categories.Books %}

[单本阅读](#single-books) · [主题阅读](#themes)

<h2 id="single-books">单本阅读</h2>

记录一本书值得推荐的地方，也留下阅读中的疑问和思考。

{% assign branch_posts = category_posts | where: "section", "single-books" %}
{% if branch_posts.size > 0 %}
<ul>
{% for post in branch_posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a> — <time datetime="{{ post.date | date: '%Y-%m-%d' }}">{{ post.date | date: "%Y-%m-%d" }}</time></li>
{% endfor %}
</ul>
{% else %}
这里还没有文章，慢慢积累。
{% endif %}

<h2 id="themes">主题阅读</h2>

围绕一个主题分享书单，联系不同作品，随着阅读持续补充。

{% assign branch_posts = category_posts | where: "section", "themes" %}
{% if branch_posts.size > 0 %}
<ul>
{% for post in branch_posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a> — <time datetime="{{ post.date | date: '%Y-%m-%d' }}">{{ post.date | date: "%Y-%m-%d" }}</time></li>
{% endfor %}
</ul>
{% else %}
这里还没有文章，慢慢积累。
{% endif %}

{% assign has_unclassified = false %}
{% for post in category_posts %}
{% if post.section != "single-books" and post.section != "themes" %}{% assign has_unclassified = true %}{% endif %}
{% endfor %}
{% if has_unclassified %}
<h2>尚未细分的文章</h2>
<ul>
{% for post in category_posts %}
{% if post.section != "single-books" and post.section != "themes" %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a> — <time datetime="{{ post.date | date: '%Y-%m-%d' }}">{{ post.date | date: "%Y-%m-%d" }}</time></li>
{% endif %}
{% endfor %}
</ul>
{% endif %}

---

[← 全部分类]({{ "/categories/" | relative_url }}) · [返回首页]({{ "/" | relative_url }})
