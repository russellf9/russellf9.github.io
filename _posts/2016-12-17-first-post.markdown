---
layout: post
title:  "Welcome to Factornine!"
date:   2016-12-17 17:35:15 +0000
categories: learning jekyll
---

A new blog for Factornine?

Lets see if this is going to be easy!


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>