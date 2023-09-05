---
title: "News"
layout: textlay
excerpt: "SARB Macro Lab at the University of Pretoria"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline | markdownify}}</em></p>
{% endfor %}
