---
title: "Overview"
---

Human Capital in the Nordic Countries is an international collaboration between computer scientists, economists, historians and other social scientists. The project is developing and applying novel machine learning techniques to harvest data from an extensive range of source materials dating back to the 1600’s relating to educational attainment across northern Europe. We have commenced work on records from Denmark and Norway, with Sweden and Finland to come later.

[Read more](about) about the project.

## Sources
{% assign sourceslist = site.sources %}
{% for item in sourceslist %}
  {% if item.slug == "index" %}
  {% else %}
  - <a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a>
  {% endif %}
{% endfor %}

## Data mapping
- [Variables](variables)
- Flowchart (to come)

## Articles
{% assign articleslist = site.articles %}
{% for item in articleslist %}
  {% if item.slug == "index" %}
  {% else %}
  - <a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a>{% if item.subtitle %}: {{ item.subtitle }}{% endif %}
  {% endif %}
{% endfor %}
