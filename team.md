---
layout: page
title: Our Team
---

<div class="people">
  {% for entry in site.people %}
    {% assign username = entry[0] %}
    {% include people.html username=username %}
  {% endfor %}
</div>
