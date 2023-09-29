---
title: "News"
layout: textlay
excerpt: "Universal Transfer Learning Lab at Korea University."
sitemap: false
permalink: /utlnews.html
---

# News

{% for article in site.data.news %}
<br />
<br />
<font color="#0000A0"> {{ article.date }} </font>
{{ article.headline | markdownify}}

{% endfor %}
