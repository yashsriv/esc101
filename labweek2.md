---
layout: page
title: "Lab Week 2"
permalink: /labweek2/
---

The first "real" labs. Most of these just comprised of
basic printing of escape sequences or special values.

Very easy and most probably no one will see this ever.

<ul class="collection with-header">
  <li class="collection-header"><h4>Posts</h4></li>
{% for post in site.posts %}
  {% if post.categories contains "labweek2" %}
    <li class="collection-item"><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>

