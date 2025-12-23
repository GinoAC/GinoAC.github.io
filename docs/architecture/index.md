---
title: Architecture
section: architecture
tags: [architecture]
---

{% include nav.html %}

Posts on computer architecture, speculation, and microarchitectural security.

{% for post in site.posts %}
  {% if post.section == "architecture" %}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
  {% endif %}
{% endfor %}
