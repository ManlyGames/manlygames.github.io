---
layout: base
title: News
permalink: /news/
---

{% for page in site.categories.news %}
<a href="{{ page.url }}">{{ page.title }}</a>
{% endfor %}
