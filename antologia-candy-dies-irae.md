---
layout: page
title: "Candy Dies Irae"
permalink: /antologia/candy-dies-irae/
---

# Candy Dies Irae

jovem não-binárie revoltade com o mundo, mas ainda assim apaixonade pela vida, mesmo que perdide. filhe de hebe e epifânia, nete de íris, paciente de santiague

<ul>
  {% for post in site.posts %}
    {% if post.antologia == "Candy Dies Irae" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
