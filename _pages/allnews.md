---
title: "News"
layout: textlay
excerpt: "AI/ML Lab at BITS Pilani"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
