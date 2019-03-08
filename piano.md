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
		<a class="poem-title" href="{{ composition.url | prepend: site.baseurl }}">
			<img src="{{ site.baseurl }}/compositions/{{ composition.image }}" width="600">
		</a>
      </li>
{% endfor %}
</ul>