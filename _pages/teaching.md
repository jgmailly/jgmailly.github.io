---
layout: page
permalink: /teaching/
title: Teaching
description:
nav: true
nav_order: 3
---

{% for teaching in site.teaching %}
<ul>
<li>
<a href="{{ teaching.url }}">
{{ teaching.title }} - {{ teaching.description }}
</a>
</li>
</ul>
<!--<p>{{ teaching.content | markdownify }}</p>-->
{% endfor %}
