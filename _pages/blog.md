---
layout: archive
classes: wide
permalink: /blog/
author_profile: true
comments: true
---

<h3 class="archive__subtitle">Posts</h3>

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
