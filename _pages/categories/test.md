---
layout: category
title: "test"
category: test
permalink: /categories/test/
---

<h1>Test 카테고리</h1>
<ul>
  {% for post in site.categories.test %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
