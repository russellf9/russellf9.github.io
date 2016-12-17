---
layout: post
title:  "Welcome to Factornine!"
date:   2016-12-17 17:35:15 +0000
categories: learning jekyll
---

A new blog for Factornine

Using the docs on [https://jekyllrb.com/](https://jekyllrb.com/)

Hosting using [Git hub pages](https://pages.github.com/)


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>