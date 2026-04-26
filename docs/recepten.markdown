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
    </a> - {{ recept.soort }} - {{ recept.keuken }}
  </h2>
{% endfor %}

