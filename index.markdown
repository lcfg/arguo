---
title: Index
date: 2016-11-20 00:38:00 Z
permalink: "/"
Field name: 
---

**Arguō.** Written and maintained by L. Greven.

{% for page in site.notes %}
  [{{ page.title }}]({{ page.url }}) published on {{ page.date | date: '%B %d, %Y' }}
{% endfor %}
