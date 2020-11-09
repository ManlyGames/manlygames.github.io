---
layout: base
title: News
permalink: /news/
---

{% for page in site.categories.news %}
<a href="{{ page.url }}" style="color:#fa8231">{{ page.title }}</a>
{% endfor %}
