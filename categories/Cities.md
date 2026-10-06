---
layout: page
title: Ways of Seeing a City
permalink: /categories/Cities/
---

尝试看见城市。

{% assign category_posts = site.categories.Cities %}

[认识城市的方法](#reading-the-city) · [在城市里生活](#small-adventures)

[建筑 →]({{ '/categories/Cities/architecture/' | relative_url }})

<h2 id="reading-the-city">认识城市的方法</h2>

{% assign branch_posts = category_posts | where: "section", "reading-the-city" %}
{% if branch_posts.size > 0 %}
<ul>
{% for post in branch_posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a> — <time datetime="{{ post.date | date: '%Y-%m-%d' }}">{{ post.date | date: "%Y-%m-%d" }}</time></li>
{% endfor %}
</ul>
{% else %}
这里还没有文章，慢慢积累。
{% endif %}

<h2 id="small-adventures">在城市里生活</h2>

{% assign branch_posts = category_posts | where: "section", "small-adventures" %}
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
{% if post.section != "reading-the-city" and post.section != "small-adventures" %}{% assign has_unclassified = true %}{% endif %}
{% endfor %}
{% if has_unclassified %}
<h2>尚未细分的文章</h2>
<ul>
{% for post in category_posts %}
{% if post.section != "reading-the-city" and post.section != "small-adventures" %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a> — <time datetime="{{ post.date | date: '%Y-%m-%d' }}">{{ post.date | date: "%Y-%m-%d" }}</time></li>
{% endif %}
{% endfor %}
</ul>
{% endif %}

---

[← 全部分类]({{ "/categories/" | relative_url }}) · [返回首页]({{ "/" | relative_url }})
