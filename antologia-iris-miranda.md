---
layout: page
title: "Íris Miranda"
permalink: /antologia/iris-miranda/
nav_exclude: true
---

# Íris Miranda

velha nostálgica, angustiada, natimorta e meio piegas. sua irmã gaia gralhão foi abortada antes de nascer e íris morreu na pandemia de covid 19.

<ul>
  {% for post in site.posts %}
    {% if post.antologia == "Íris Miranda" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
