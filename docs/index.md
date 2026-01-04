---
title: Home
---

My personal site to blog about architecture, coding, hacking, books, the outdoors, and whatever has caught my bucaneer fancy.

## Recent Posts

{% for post in site.posts limit:10 %}
### [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{{ post.excerpt | strip_html }}
{% endfor %}
