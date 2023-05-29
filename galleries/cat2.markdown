---
layout: gallery
title: Category 2
permalink: /galleries/cat2/
---

<div>
	{% for item in site.data.gallerydata %}
			{% if item.category == "cat2" and item.active == 1 %}
				<div>{{item.url}}</div>
				<div>{{item.title }}</div>
				<div>{{item.description}}</div>
			{% endif %}
	{% endfor %}
</div>