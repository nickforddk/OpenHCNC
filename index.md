---
title: "Overview"
cover: front.jpg
---

*Human Capital in the Nordic Countries* is a project to catalogue educational attainment across Denmark, Norway, Sweden and Finland over the long term. Our goal is to unlock access to an extensive range of detailed student-level information in order to explore the contribution of education to Scandinavia's economic development. We use state-of-the-art machine learning techniques to transcribe historic source material, with this data in turn linked to population-wide registers (such as census records). You can [read more about the project](about).

The HCNC project is a collaborative endeavour, drawing on researchers at universities and partner institutions in Denmark, Norway and Sweden.

<div class="grid">
  <div>
    <h2><a href="{{ site.baseurl }}/sources">Sources</a></h2>
    {% assign sourceslist = site.sources %}
    <ul>
    {% for item in sourceslist %}
      {% if item.slug == "index" %}
      {% else %}
      <li><a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a></li>
      {% endif %}
    {% endfor %}
    </ul>

    <h2>Data mapping</h2>
    <ul>
      <li><a href="{{ site.baseurl }}/variables">Variables</a></li>
      <li>Flowchart (to come)</li>
    </ul>
  </div>

  <div>
    <h2><a href="{{ site.baseurl }}/articles">Articles</a></h2>
    {% assign articleslist = site.articles %}
    <ul>
    {% for item in articleslist %}
      {% if item.slug == "index" %}
      {% else %}
      <li><a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a>{% if item.subtitle %}: {{ item.subtitle }}{% endif %}</li>
      {% endif %}
    {% endfor %}
    </ul>
  </div>
</div>
