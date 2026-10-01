---
layout: page
title: Ways of Seeing a City
permalink: /categories/Cities/
---

用不同的方法认识一座城市，也记录一个人在城市里的小探索。

{% assign category_posts = site.categories.Cities %}

[认识城市的方法](#reading-the-city) · [一个人的小探索](#small-adventures)

<h2 id="reading-the-city">认识城市的方法</h2>

沿着地铁、河流、街道或其他线索，观察城市的结构和变化。

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

<h2 id="small-adventures">一个人的小探索</h2>

跟着别人分享的路线骑行，去工业园里的工厂店，看看商品从哪里出发。把一个发现变成一次出门的起点。

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
