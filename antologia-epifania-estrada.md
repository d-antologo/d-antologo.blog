---
layout: page
title: "Epifânia Estrada"
permalink: /antologia/epifania-estrada/
nav_exclude: true
---

# Epifânia Estrada

mulher lúcida, bem compreendida das coisas do mundo real, mas às vezes fica perdida e não consegue se entender. esposa de hebe frênica, filha de íris miranda, mãe de candy dies irae.

<ul>
  {% for post in site.posts %}
    {% if post.antologia == "Epifânia Estrada" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
