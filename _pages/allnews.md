---
title: "CIBeR @ USF - News"
layout: textlay
excerpt: "CIBeR @ USF - News"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
{{ article.date }} <br>
{{ article.headline | markdownify}}
{% endfor %}
