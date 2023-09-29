---
title: "News"
layout: textlay
excerpt: "Universal Transfer Learning Lab at Korea University."
sitemap: false
permalink: /utlnews.html
---

# News

{% for article in site.data.news %}
<font color="#0000A0"> {{ article.date }} </font><br />
<b>{{ article.headline | markdownify}}</b> <br />
{% endfor %}
