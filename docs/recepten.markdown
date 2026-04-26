---
layout: page
title: Recepten
permalink: /recepten/
---

Hier staan al mijn recepten:

{% for recept in site.recepten %}
  <h3>
    <a href="{{ recept.url }}">
      {{ recept.naam }}
    </a>
 ({{ recept.soort }}, {{ recept.keuken }})
  </h3>
{% endfor %}
