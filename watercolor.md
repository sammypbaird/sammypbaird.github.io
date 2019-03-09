---
layout: page
permalink: /portfolio/watercolor/
title: watercolor
folder: portfolio
---

<ul class="post-list">
{% for piece in site.watercolor %}
	{% include portfolioPreview.html %}
{% endfor %}
</ul>