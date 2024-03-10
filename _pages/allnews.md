---
title: "News"
layout: textlay
excerpt: "Cryptology at Inha University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<div class="news-item">
  <span class="news-date">{{ article.date }}</span><br>
  <span class="news-headline">{{ article.headline }}</span>
</div>
{% endfor %}
