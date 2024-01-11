---
title: Tutorials
layout: page
description: Tutorials on Magia and Digital Design
---

Welcome to the tutorials section. Here you will find tutorials on Magia and Digital Design.

{% 
assign tutorials = site.pages 
| where_exp: "item", "item.dir contains '/tutorial/'" 
| sort: "step"
%}
{% for t in tutorials %}
1. [{{ t.title }}]({{ site.baseurl }}{{ t.url }})
{% endfor %}
