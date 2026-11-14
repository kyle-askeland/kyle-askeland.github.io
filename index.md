---
layout: default
title: Home
description: Personal website of Kyle Askeland, software engineer focused on cybersecurity and cloud applications.
---
<section class="hero">
  <p class="eyebrow">SOFTWARE ENGINEER · CYBERSECURITY</p>
  <h1>Building useful things.<br><span class="muted-heading">Writing about the process.</span></h1>
  <p class="lede">I'm Kyle, a software engineer working across cybersecurity, backend systems, and cloud infrastructure. This is where I share projects, technical notes, and lessons learned.</p>
  <div class="hero-links"><a class="primary-link" href="/projects/">Explore projects <span aria-hidden="true">↗</span></a><a class="text-link" href="/blog/">Read the blog →</a></div>
</section>
<section class="section">
  <div class="section-heading"><h2>What I work with</h2></div>
  <div class="pill-row"><span>Go</span><span>AWS</span><span>Security engineering</span><span>Terraform</span><span>PostgreSQL</span><span>CI/CD</span></div>
</section>
<section class="section">
  <div class="section-heading"><h2>Recent writing</h2><a href="/blog/">All posts →</a></div>
  {% assign recent_posts = site.posts | slice: 0, 3 %}
  {% if recent_posts.size > 0 %}
  <div class="post-list">{% for post in recent_posts %}<a class="post-row" href="{{ post.url | relative_url }}"><div><span class="post-meta">{{ post.date | date: '%b %-d, %Y' }}</span><h3>{{ post.title | escape }}</h3><p>{{ post.description | default: post.excerpt | strip_html | truncatewords: 22 }}</p></div><span aria-hidden="true">↗</span></a>{% endfor %}</div>
  {% else %}<p class="quiet">Posts are coming soon. Check back after the first article is published.</p>{% endif %}
</section>
