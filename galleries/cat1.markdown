---
layout: gallery
title: Category 1
permalink: /galleries/cat1/
---

<div>
	{% for item in site.data.gallerydata %}
			{% if item.category == "cat1" and item.active == 1 %}
				<div>{{item.url}}</div>
				<div>{{item.title }}</div>
				<div>{{item.description}}</div>
			{% endif %}
	{% endfor %}
</div>