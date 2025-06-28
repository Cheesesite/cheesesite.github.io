---
layout: default
title: Blog
permalink: /blog.html
---

# Cheese Blog

Welcome to the cheese blog. Below are the latest posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span> – {{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
