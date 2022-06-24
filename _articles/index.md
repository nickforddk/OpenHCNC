---
title: "Articles"
layout: default
---

{% assign articleslist = site.articles | where:"layout", "article" %}
{% for item in articleslist %}
- <a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a>: {{ item.subtitle }}
{% endfor %}
