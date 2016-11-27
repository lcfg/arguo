---
title: Index
date: 2016-11-20 00:38:00 Z
permalink: "/"
Field name: 
---

<LINK href="css/_typeplate-index.css" rel="stylesheet" type="text/css">

**Arguō.** Written and maintained by L. Greven.



{% for page in site.notes %}
  [{{ page.title }}]({{ site.url }}/articles) published on {{ page.date | date: '%B %d, %Y' }}
{% endfor %}
