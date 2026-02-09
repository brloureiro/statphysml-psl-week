---
layout: default
title: Statistical Physics and Machine Learning
permalink: /
---

{% assign meta = site.data.editions %}
{% assign current_ed = meta.editions | where: "id", meta.current | first %}

<meta http-equiv="refresh" content="0; url={{ current_ed.url }}">
<link rel="canonical" href="{{ current_ed.url }}">

Redirecting to the current edition:
[{{ current_ed.id }}]({{ current_ed.url }})
