---
layout: page
title: Blog
permalink: /blog/
---

This page lists all published posts.

{% if site.posts.size > 0 %}
<ul class="post-list">
  {% for post in site.posts %}
  <li>
    <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
    <h3>
      <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
    </h3>
  </li>
  {% endfor %}
</ul>
{% else %}
No posts yet.
{% endif %}
