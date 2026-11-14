---
layout: default
title: Home
---

# Kyle Askeland

I'm a software engineer working in cybersecurity and cloud infrastructure. I enjoy writing about my experiences in this field, whether it be my opinions or things I've created.

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
