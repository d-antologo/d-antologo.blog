---
layout: page
title: "Hebe Frênica"
permalink: /antologia/hebe-frenica/
nav_exclude: true
---

# Hebe Frênica

mulher confusa, taxada de louca por muitos, mas muito lúcida da própria linguagem. esposa de epifânia e mãe de candy.

<ul>
  {% for post in site.posts %}
    {% if post.antologia == "Hebe Frênica" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
