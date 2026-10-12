---
layout: default
title: Notes from YC
---

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
