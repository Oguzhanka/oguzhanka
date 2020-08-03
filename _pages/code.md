---
layout: archive
title: "Code"
permalink: /_code/
author_profile: true
classes: wide
---

{% for post in site.code reversed %}
  {% include archive-single.html %}
{% endfor %}
