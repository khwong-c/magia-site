---
title: Playgrounds
layout: page
description: Tutorials on Magia and Digital Design
---

You can try out Magia without installing anything on your computer.<br/>
Just click on the links below to launch the online playgrounds.

{% for item in site.data.playgrounds %}

1. [{{ item.name }}]({{ item.url }})
- {{ item.description }}
<br/><br/>
{% endfor %}
