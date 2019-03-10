---
layout: page
permalink: /portfolio/pencil/
title: pencil
folder: portfolio
---

<ul class="post-list">
{% for piece in site.pencil %}
	{% include portfolioPreview.html %}
{% endfor %}
</ul>