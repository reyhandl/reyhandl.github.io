---
layout: page
title: Writing
permalink: /writing/
nav: true
nav_order: 5
---

Notes and posts about research, learning, and ideas.

{% if site.posts.size > 0 %}
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%b %-d, %Y" }})</small>
    </li>
  {% endfor %}
</ul>
{% else %}
No posts yet.
{% endif %}
