---
layout: page
title: Recepten
permalink: /recepten/
---

Hier staan al mijn recepten:

{% for recept in site.recepten %}
  <h2>{{ recept.naam }}</h2>
  <h3>{{ recept.soort }} - {{ recept.keuken }}</h3>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}

