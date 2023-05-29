---
layout: gallery
title: Category 3
permalink: /galleries/cat3/
---

<div>
	{% for item in site.data.gallerydata %}
			{% if item.category == "cat3" and item.active == 1 %}
				<div>{{item.url}}</div>
				<div>{{item.title }}</div>
				<div>{{item.description}}</div>
			{% endif %}
	{% endfor %}
</div>