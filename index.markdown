---
title: Index
date: 2016-11-20 00:38:00 Z
permalink: "/"
---

Welcome.

{% for page in site.pages %}
  [{{ page.title }}]({{ page.url }})
{% endfor %}
