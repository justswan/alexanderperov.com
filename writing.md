---
layout: page
title: Writing
permalink: /writing
---

Things I've written. Mostly notes about art, school, and things I'm figuring out.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %Y" }}
{% endfor %}
