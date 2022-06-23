---
title: "Articles"
layout: default
---

# Articles
{% assign articleslist = site.articles | where:"layout", "article" %}
{% for item in articleslist %}
- <a href="{{ item.url }}">{{ item.title }}</a>: {{ item.subtitle }}
{% endfor %}
