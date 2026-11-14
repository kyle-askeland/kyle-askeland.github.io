---
layout: default
title: Home
---

# Kyle Askeland

I'm a software engineer working in cybersecurity, backend development, and cloud infrastructure. I write about projects, technical problems, and things I learn along the way.

## Posts

{% if site.posts.size > 0 %}
<ul class="post-list">
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
    <small>{{ post.date | date: "%b %-d, %Y" }}</small>
  </li>
{% endfor %}
</ul>
{% else %}
No posts yet.
{% endif %}
