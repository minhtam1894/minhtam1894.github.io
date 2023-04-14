---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

In recent years, there has been a growing interest in developing innovative technologies for improving the performance and durability of asphalt concrete, a widely used material in the construction industry for roadways, parking lots, and other infrastructure projects. Among these technologies, 3D printing, black ice prediction programs, microencapsulated phase change materials, microwave self-healing, and induction self-healing are some of the most promising approaches that have been extensively researched and developed in the past few years. These technologies aim to enhance the mechanical, thermal, and self-healing properties of asphalt concrete, which can ultimately lead to a longer lifespan and reduced maintenance costs. In this research, we will explore these innovative technologies and their potential applications in asphalt concrete construction.


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
