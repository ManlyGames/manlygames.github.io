---
layout: base
title: News
permalink: /news/
---

{% for page in site.categories.news %}
<a href="{{ page.permalink }}">{{ page.title }}</a>
{% endfor %}
