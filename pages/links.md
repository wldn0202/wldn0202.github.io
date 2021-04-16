---
layout: page
title: Links
description: 링크
keywords: 링크
comments: false
menu: 링크
permalink: /links/
---

> To climb steep hills requires slow pace at first.

{% for link in site.data.links %}
  {% if link.src == 'life' %}
* [{{ link.name }}]({{ link.url }})
  {% endif %}
{% endfor %}

> 링크

{% for link in site.data.links %}
  {% if link.src == 'www' %}
* [{{ link.name }}]({{ link.url }})
  {% endif %}
{% endfor %}
