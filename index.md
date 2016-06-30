---
layout: page
title: Introduction
tagline: You've reached level 0
---
{% include JB/setup %}

This website is where I'm writing down my endevours into math,
physics, and programming.  Much of the concepts and work I'll talk
about here are going to be directed towards either my
simulation/rendering system pet project or high-dimensional/complex
math and its relation to physics.

## Posts

For now here is a list of my posts, this will most likely be updated
later:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

