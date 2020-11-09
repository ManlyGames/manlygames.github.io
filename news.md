---
layout: base
title: News
permalink: /news/
---

{% for news in site.categories.news %}
<a href="{{ news.permalink }}">{{ news.title }}</a>
{% endfor %}
