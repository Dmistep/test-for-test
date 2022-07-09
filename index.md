---
layout: default
title: Мой блог.
---

{% assign page = site.posts.first %}
{% assign content = page.content %}
{% include post.html %}
