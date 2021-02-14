---
layout: default
title: 成员
description: ————
permalink: /staff.html
content_at_off: true
---
<ul>
  {% for author in site.authors %}
    <li>
      <h2><a href="{{ author.url }}">{{ author.name }}</a> | {{ author.position }}</h2>
      <p>{{ author.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>
