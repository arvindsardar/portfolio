---
layout: gallery
title: Category 4
permalink: /galleries/cat4/

---

<div>
	{% for item in site.data.gallerydata %}
			{% if item.category == "cat4" and item.active == 1 %}
				<div>{{item.url}}</div>
				<div>{{item.title }}</div>
				<div>{{item.description}}</div>
			{% endif %}
	{% endfor %}
</div>