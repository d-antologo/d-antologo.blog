---
layout: page
title: "Anne von Dotta"
permalink: /antologia/anne-von-dotta/
---

# Anne von Dotta

drag queen inteligente e comunicativa, engraçada, àcida e crítica. irmã de geni bat papo, com quem divide um podcast.

<ul>
  {% for post in site.posts %}
    {% if post.antologia == "Anne von Dotta" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
