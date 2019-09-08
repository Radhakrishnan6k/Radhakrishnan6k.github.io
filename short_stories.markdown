---
layout: page
heading: Short stories
title:  "Short stories"
permalink: /short_stories
---

{% for post in site.posts %} {% if post.categories contains 'short_stories' %} {% if post.class contains 'Short stories' %}
.<a href="{{ post.permalink }}">{{ post.title }}</a>

{% endif %} {% endif %} {% endfor %}
