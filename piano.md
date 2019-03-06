---
layout: page
permalink: /piano/
title: piano
description: Piano compositions
menu: true
---

<ul class="post-list">
{% for composition in site.piano reversed %}
    <li>
        <h2><a class="poem-title" href="{{ composition.url | prepend: site.baseurl }}">{{ composition.title }}</a></h2>
        <p class="post-meta">{{ composition.date | date: '%B %-d, %Y' }}</p>
      </li>
{% endfor %}
</ul>