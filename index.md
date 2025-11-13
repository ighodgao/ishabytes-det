---
layout: default
title: "Home"
---

# Isha’s writing

Welcome! This is an archive of my older blog posts.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small> ({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endfor %}
</ul>
