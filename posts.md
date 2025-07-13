---
layout: page
title: "All Posts"
permalink: /posts/
---

# All Posts

{% raw %}{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt | strip_html | truncatewords: 50 }}

**Categories:** {% for category in post.categories %}{{ category }}{% unless forloop.last %}, {% endunless %}{% endfor %}

**Tags:** {% for tag in post.tags %}{{ tag }}{% unless forloop.last %}, {% endunless %}{% endfor %}

---

{% endfor %}{% endraw %}

---

[← Back to Writing](/writing/) 