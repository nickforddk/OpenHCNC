---
title: "Articles"
layout: default
---

# Articles
1. [Education and industrialisation (descriptive)](descriptives)
2. [Lessons from Oslo](oslo)

{% for article in site.articles %}
- <a href="{{ article.url }}">{{ article.title }}</a>: {{ article.subtitle }}
{% endfor %}
