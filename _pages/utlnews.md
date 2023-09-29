---
title: "News"
layout: textlay
excerpt: "Universal Transfer Learning Lab at Korea University."
sitemap: false
permalink: /utlnews.html
---

# News

{% for article in site.data.news %}
{{ article.date }} <br>
{{ article.headline | markdownify}}
{% endfor %}
