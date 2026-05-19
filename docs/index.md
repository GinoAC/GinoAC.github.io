---
title: Home
---

A blog covering computer architecture, microarchitectural security, systems programming, and research. Expect occasional detours into books, music, and whatever else is on my mind. 

## Recent Posts

{% for post in site.posts limit:10 %}
### [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{{ post.excerpt | strip_html | truncatewords: 40}}
{% endfor %}
