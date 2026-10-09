---
layout: page
permalink: /papers/
title: Accepted Papers
description: Accepted papers at SPIGM @ ICLR 2027, listed by paper ID.
nav: false
nav_order: 5
---

<br>

<ul>
{% for paper in site.data.papers %}
  <li><strong>{{ paper.id }}</strong>. <a href="{{ paper.forum }}" target="_blank" rel="noopener noreferrer">{{ paper.title }}</a></li>
{% endfor %}
</ul>
