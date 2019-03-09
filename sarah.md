---
layout: page
permalink: /sarah
title: Sarah
---

<ul class="post-list">
{% for piece in site.sarah %}
	{% include portfolioPreview.html %}
{% endfor %}
</ul>