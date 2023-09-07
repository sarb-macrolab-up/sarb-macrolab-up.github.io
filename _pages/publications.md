---
title: "SARB Macro Lab at Tuks - Publications"
layout: gridlay
excerpt: "Allan Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Research

{% for publi in site.data.publist %}


  {{ publi.authors }} <br /><a href="{{ publi.link.url }}">{{ publi.link.display }} <br />
  <em>{{ publi.title }}
  <p>{{ publi.description }}</p>

{% endfor %}
