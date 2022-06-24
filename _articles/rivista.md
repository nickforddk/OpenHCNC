---
title: "Leaving their mark"
subtitle: "Using Danish student grade lists to construct a more detailed measure of historical human capital"
layout: default
status: completed
members: [Sharp, Ranestad, Ford]
---

We provide a brief overview of the educational history of Denmark and document archival and printed sources covering the development of primary, secondary, and tertiary education. In particular, we focus on student grade lists, which are available for individuals at all levels of education from the early Nineteenth century until well into the Twentieth century. We suggest that these can be used to construct more detailed measures of human capital than those usually employed, making it possible to deconstruct aggregate levels and types of education into e.g., science or humanities, as well as to measure the extent to which this was actually learned, as captured by the grades achieved. Given the role usually attributed to human capital for development, and perhaps particularly with regards to the Nordic countries, such data has the potential to greatly increase our understanding of how Denmark became the rich and successful country it is today.

This article is available at the [Italian Review of Economic History](https://www.rivisteweb.it/doi/10.1410/102500).

{% assign team_members = site.team | sort: "surname" %}
<ul class="bio">
{% for team_member in team_members %}
  {% if team_member.surname == page.members %}
  <li><span>{{ team_member.firstname }} <span>{{ team_member.surname }}</span></span>
    <ul>
      <li>{{ team_member.position }}</li>
      <li>{{ team_member.institution }}</li>
      {% if team_member.website != "" %}<li class="buttons website"><a href="{{ team_member.website }}"></a></li>{% endif %}
      {% if team_member.twitter != "" %}<li class="buttons twitter"><a href="https://www.twitter.com/{{ team_member.twitter }}"></a></li>{% endif %}
      {% if team_member.github != "" %}<li class="buttons github"><a href="https://www.github.com/{{ team_member.github }}"></a></li>{% endif %}
    </ul>
  </li>
  {% endif %}
{% endfor %}
</ul>
