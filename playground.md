---
title: Playgrounds
layout: page
description: Tutorials on Magia and Digital Design
---

Welcome to the tutorials section. Here you will find tutorials on Magia and Digital Design.


{% for item in site.data.playgrounds %}
1. [{{ item.name }}]({{ item.url }})
{% endfor %}
