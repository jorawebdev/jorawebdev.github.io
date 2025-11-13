---
layout: default  # Use the default layout created in _layouts
title: Custom Web Development  # Title of the page
description: zElement: Custom Web Development Services.  # Short description
---

# Welcome to zElement

This is my first Jekyll site hosted on GitHub Pages. Here, you can find my blog posts and other content.

## About Me

I am passionate about [your interests or topics] and love to share knowledge through my blog.

## Recent Posts

You can view my latest blog posts below:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
