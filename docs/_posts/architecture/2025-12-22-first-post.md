---
title: First Post
section: architecture
tags: [architecture, security]
---

Intro paragraph.

<!--more-->

Rest of post.

---

**Tags:**
{% for tag in page.tags %}
[`{{ tag }}`]({{ site.baseurl }}/tags/#{{ tag | slugify }})
{% endfor %}
