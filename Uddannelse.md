---
layout: page
title: Uddannelse
---
{% for item in site.data.resume.education %}
  {% include education.html
     titel=item.titel
     sted=item.sted
     start=item.start
     slut=item.slut
     beskrivelse=item.beskrivelse %}
{% endfor %}