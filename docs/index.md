---
title: Home
---

{% include nav.html %}

## Recent Posts

{% for post in site.posts limit:5 %}
### [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{{ post.excerpt | strip_html }}
{% endfor %}
