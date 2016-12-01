---
title: Index
date: 2016-11-20 00:38:00 Z
permalink: "/"
Field name: 
---

## Arguō
Maintained by Laurens.
Last update: {{ page.date | date: '%B %d, %Y' }}

**Recent links**
{% for page in site.notes %}

[{{ page.title }}]({{ site.url }}/articles) - tags: {% for tag in page.categories %}{{ tag }}, {% endfor %}
{% endfor %}

**Recent images**
{% for page in site.images %}

[{{ page.title }}]({{ site.url }}/articles) - tags: {% for tag in page.categories %}{{ tag }} {% endfor %}
{% endfor %}