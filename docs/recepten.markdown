---
layout: page
title: Recepten
permalink: /recepten/
---

Hier staan al mijn recepten:

{% for recept in site.recepten %}
  <h2>
    <a href="{{ recept.url }}"
      {{ recept.naam }}
    </a>
  </h2>
  <h3>{{ recept.soort }} - {{ recept.keuken }}</h3>
{% endfor %}

