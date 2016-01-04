---
layout: page
title: Zepinto's Code Blog
tagline: if (idle) { // write blog post }
---
{% include JB/setup %}

## About
My intention with this blog is to post about personal discoveries and/or developed
code that can be useful to anyone. A lot of times I will be covering developments
made at the lab where I work (@lsts) concerning robotics / networking.

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
