---
layout: page
title: Erhvervserfaring
---
{% for item in site.data.resume.experience %}
  {% include experience.html
     titel=item.titel
     firma=item.firma
     location=item.location
     start=item.start
     slut=item.slut
     beskrivelse=item.beskrivelse %}
{% endfor %}