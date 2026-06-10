---
layout: page
title: "Geni Bat Papo"
permalink: /antologia/geni-bat-papo/
nav_exclude: true
---

# Geni Bat Papo

drag queen inteligente e comunicativa, profunda, reflexiva e meio prolixa. irmã de santiague e anne (com quem divide um podcast).

<ul>
  {% for post in site.posts %}
    {% if post.antologia == "Geni Bat Papo" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
