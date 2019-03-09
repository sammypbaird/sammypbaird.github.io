---
layout: page
permalink: /sarah
title: sarah
---

<ul class="post-list">
{% for piece in site.sarah %}
	{% include portfolioPreview.html %}
{% endfor %}
</ul>