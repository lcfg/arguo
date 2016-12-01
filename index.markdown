---
title: Index
date: 2016-11-20 00:38:00 Z
permalink: "/"
Field name: 
---

<LINK href="{{site.url}}/css/materialize.min.css" rel="stylesheet" type="text/css">
<div class="container">

Arguō
Maintained by Laurens.

<div class="collection">
<a href="#!" class="collection-item"><span class="badge">{{ page.date | date: '%B %d, %Y' }}</span>Last update</a>
</div>

{% for page in site.notes %}
[{{ page.title }}]({{ site.url }}/articles) -
tagged with: {% for tag in page.categories %}{{ tag }}, {% endfor %}
{% endfor %}

</div>