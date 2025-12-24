---
title: Architecture
section: architecture
tags: [architecture]
---

Posts on computer architecture, speculation, and microarchitectural security.

{% for post in site.posts %}
  {% if post.section == "architecture" %}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
  {% endif %}
{% endfor %}
