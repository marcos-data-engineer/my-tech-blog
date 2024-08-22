---
layout: home
---

# Welcome to My Tech Blog

Here you'll find articles about the latest in technology, programming tips, and more!

## Recent Posts
{% for post in site.posts %}
  * [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
