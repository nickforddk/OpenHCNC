---
title: "Sources"
layout: directory
---

{% assign sourceslist = site.sources %}
{% for item in sourceslist %}
  {% if item.slug == "index" %}
  {% else %}
  1. <a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a>{% if item.subtitle %}: {{ item.subtitle }}{% endif %}
  {% endif %}
{% endfor %}
