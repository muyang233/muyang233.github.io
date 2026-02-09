---
layout: default
title: Main Page
---

# Welcome to Rain's blog! ^_^

## Latest articles
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
