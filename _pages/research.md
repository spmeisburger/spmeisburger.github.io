---
layout: archive
title: "Research Highlights"
permalink: /research/
author_profile: true
---

{% include base_path %}
<center>
{% for post in site.research %}
  {% include archive-single.html type = "grid" %}
{% endfor %}
</center>
