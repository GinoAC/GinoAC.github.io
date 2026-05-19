---
title: Home
---

A blog covering computer architecture, microarchitectural security, systems programming, and research — with occasional detours into books, music, and whatever else is on my mind. Written by a computer architecture PhD with a focus on memory systems, performance, and security.

## Recent Posts

{% for post in site.posts limit:10 %}
### [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{{ post.excerpt | strip_html | truncatewords: 40}}
{% endfor %}
