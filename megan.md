---
layout: page
permalink: /megan
title: Megan
---

<ul class="post-list">
{% for piece in site.megan %}
	{% include portfolioPreview.html %}
{% endfor %}
</ul>