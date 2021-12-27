---
title: Buildings at Strand Campus, King's College London
layout: index
---

{% for building in site.buildings %}

<p>{{ building.title }}</p>
<p>{{ building. history }}</p>

{% endfor %}