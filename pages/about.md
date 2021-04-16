---
layout: page
title: About
description: about
keywords: main
comments: true
menu: 소개
permalink: /about/
---

컴퓨터 비전을 공부하는 학생입니다.

## 계정

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
