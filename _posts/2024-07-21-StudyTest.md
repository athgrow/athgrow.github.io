---
title: "Study 카테고리 생성test"
subtitle: ""
layout: archive
author_profile: true
sidebar_main: true
permalink: categories/Study
categories:
 - Study
tags: [Study]  # 해시태그를 여기에 입력하세요
excerpt: "공부한 것을 정리합니다."
---


{% assign posts = site.categories.Study %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}


카테고리 생성이 제대로 되는지 테스트 중입니다. Study 카테고리가 생성되어야합니다.
