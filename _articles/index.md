---
title: "Articles"
layout: default
---

{% assign articleslist = site.articles %}
{% for item in articleslist %}
  {% if item.slug == "index" %}
  {% else %}
  1. <a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a>{% if item.subtitle %}: {{ item.subtitle }}{% endif %}
  {% endif %}
{% endfor %}
