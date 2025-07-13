---
layout: page
title: "Writing"
permalink: /writing/
---

# Writing

Welcome to my writing section! Here you'll find articles, thoughts, and insights I've shared.

## Recent Posts

{% raw %}{% for post in site.posts limit:5 %}
### [{{ post.title }}]({{ post.url }})
*Date: {{ post.date | date: "%B %Y" }}*

{{ post.excerpt | strip_html | truncatewords: 30 }}

{% endfor %}{% endraw %}

{% raw %}{% if site.posts.size > 5 %}
[View all posts →](/posts/)
{% endif %}{% endraw %}

[View all posts →](/posts/)

## Writing Categories

- **Technology**: Thoughts on software development, tools, and industry trends
- **Learning**: Reflections on new skills, courses, and educational experiences
- **Personal**: Insights and experiences from my journey

## Get in Touch

If you'd like to discuss any of my writing or have suggestions for future topics, feel free to reach out:

- 📧 [Email](mailto:reyhandanilambaga@email.com)
- 💻 [GitHub](https://github.com/reyhandl)

---

*This section is a work in progress. More content coming soon!* 