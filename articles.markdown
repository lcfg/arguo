---
title: Articles
date: 2016-11-20 00:15:00 Z
permalink: "/articles"
links: 
notes: 
---

# Articles

{% for page in site.notes %}
  <p class="typl8-drop-cap"> {{ page.content }} </p>
{% endfor %}
