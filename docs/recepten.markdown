---
layout: page
title: Recepten
permalink: /recepten/
---

Hier staan mijn recepten, die ik heb bedacht of verzameld:

{% for recept in site.recepten %}
  <h3>
    <a href="{{ recept.url }}">
      {{ recept.naam }}
    </a>
 ({{ recept.soort }}, {{ recept.keuken }})
  </h3>
{% endfor %}
