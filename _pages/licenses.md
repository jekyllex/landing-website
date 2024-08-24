---
layout: page
title: Licenses
include_in_header: false
---

# Licenses

{% assign licenses = site.licenses | sort: "code" %}
{% for license in licenses %}
  <h3><a href="{{ license.url }}" target="_self">{{ license.title }}</a></h3>
  <p>{{ license.description }}</p>
{% endfor %}
