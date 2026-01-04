---
title: Books-Movies-Music 
section: bmm 
tags: [BMM]
---

Here, I randomly rant about books, movies, or music. 

{% for post in site.posts %}
  {% if post.section == "bmm" %}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
  {% endif %}
{% endfor %}
