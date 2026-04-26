---
layout: page
title: Recepten
permalink: /recepten/
---

Hier staan al mijn recepten:

{% for recept in site.recepten %}
  <h2 style="display:inline;">
    <a href="{{ recept.url }}">
      {{ recept.naam }}
    </a>
  </h2>
  <p style="display:inline;"> {{ recept.soort }} - {{ recept.keuken }} </p>
{% endfor %}

