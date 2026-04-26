---
layout: page
title: Recepten
permalink: /recepten/
---

Hier staan al mijn recepten:

{% for recept in site.recepten %}
  <h2>
    <a href="{{ recept.url }}">
      {{ recept.naam }}
    </a>
  </h2>
  <p> {{ recept.soort }} - {{ recept.keuken }} </p>
{% endfor %}

{% for recept in site.recepten %}
  <h2 style="display:inline;">
    <a href="{{ recept.url }}">
      {{ recept.naam }}
    </a>
  </h2>
  <p style="display:inline;"> {{ recept.soort }} - {{ recept.keuken }} </p>
{% endfor %}

