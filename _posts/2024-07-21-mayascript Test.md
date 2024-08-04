---
layout: archive
title: "마야 스크립트 글 Test"
subtitle: ""
permalink: categories/MayaScript
categories:
 - MayaScript
tags: [VFX, MayaScript]  # 해시태그를 여기에 입력하세요
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.MayaScript %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}

