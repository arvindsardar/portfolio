---
layout: gallery
title: Category 5
permalink: /galleries/cat5/
---

<div>
	{% for item in site.data.gallerydata %}
			{% if item.category == "cat5" and item.active == 1 %}
				<div>{{item.url}}</div>
				<div>{{item.title }}</div>
				<div>{{item.description}}</div>
			{% endif %}
	{% endfor %}
</div>