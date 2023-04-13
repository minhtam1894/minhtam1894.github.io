---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My academic research falls into two main areas: research on the properites of asphalt mixture, including Hot Mix Asphalt, Warm Mix Asphalt, and Cold Mix Asphalt. 


My other main research is developed computer program black ice prediction program


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
