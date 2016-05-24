---
layout: page
title: "Lab Week 3"
permalink: /labweek3/
---

These labs involved basic Input/Output with
formatted output and some basic calculations on
the input.

<ul class="collection with-header">
  <li class="collection-header"><h4>Posts</h4></li>
{% for post in site.posts %}
  {% if post.categories contains "labweek3" %}
    <li class="collection-item"><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>

