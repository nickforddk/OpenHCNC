---
title: "Overview"
---

[About](about)

## Sources
- Grade lists
- Biographies
- Census / population register

## Variables
[Variables](variables)
- Flowchart

## Papers
{% assign articleslist = site.articles %}
{% for item in articleslist %}
  1. <a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a>{% if item.subtitle %}: {{ item.subtitle }}{% endif %} {{ item.date }}
{% endfor %}
