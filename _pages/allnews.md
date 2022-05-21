---
title: "NLP Group @ USF - News"
layout: textlay
excerpt: "NLP Group @ USF - News"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
{{ article.date }} <br>
{{ article.headline | markdownify}}
{% endfor %}
