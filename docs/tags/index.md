---
title: Tags
---

{% include nav.html %}

{% assign sorted_tags = site.tags | sort %}

{% for tag in sorted_tags %}
## {{ tag[0] }}

<ul>
{% for post in tag[1] %}
  <li>
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

{% endfor %}
