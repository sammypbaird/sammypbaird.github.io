---
layout: page
permalink: /portfolio/watercolor/
title: Watercolors
---

<ul class="post-list">
{% for piece in site.watercolor %}
	{% include portfolioPreview.html %}
{% endfor %}
</ul>