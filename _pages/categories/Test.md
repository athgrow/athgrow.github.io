---
layout: category
title: "Test"
category: test
permalink: /categories/test/
---

<h1>Test 카테고리</h1>
<ul>
  {% for post in site.categories.Test %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
