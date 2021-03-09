---
title: posts
layout: default
show_title: true
---

{% for post in site.posts %}
- [ {{ post.title }} ]( {{ post.url }} )
{% endfor %}