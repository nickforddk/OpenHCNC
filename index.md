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
  {% if item.slug != "index" %}
    
  {% else %}
  {% endif %}
{% endfor %}
