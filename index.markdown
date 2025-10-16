---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults


---
layout: page
title: Categories
permalink: /categories/
---

<ul>
  {% assign cats = site.categories | sort %}
  {% for cat in cats %}
    <li>
      <a href="{{ site.baseurl }}/categories/{{ cat[0] }}/">
        {{ cat[0] }} ({{ cat[1].size }})
      </a>
    </li>
  {% endfor %}
</ul>

