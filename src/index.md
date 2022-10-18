---
title: Hello World
layout: "base.njk"
---

Hello JamStack fan!

{% for post in collections.posts %}
- [{{post.data.title}}]({{post.url}})
{% endfor %}
