---
title: "CIBeR @ USF - News"
layout: textlay
excerpt: "CIBeR @ USF - News"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<h4> {{ article.date }} </h4>
{{ article.headline | markdownify}}
{% endfor %}
