---
layout: page
title: "Santiague Ventura"
---

# Santiague Ventura

psicólogue não-binárie, pseudofilósofe, muito esclarecide, mas cujo conhecimento muitas vezes não consegue se reverter em ajuda a seus pacientes. às vezes fica perdide, entra em greve e abandona quem mais precisa delu. terapeuta de candy e irmane de anne von dotta e geni bat papo.

<ul>
  {% for post in site.posts %}
    {% if post.antologia == "Santiague Ventura" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
